# Logger

Usage:

``` C++
	Logger::ReportingLevel() = VERBOSE;
	fopen_s(&Output::Stream(), "mylogfile.txt", "w");

	float x = 0.2f;
	double t = 546.3;
	LOG_VERBOSE << "Logging this line " << x << " " << t;
	LOG_DEBUG << "Logging this line " << x << " " << t;
	LOG_INFO << "Logging this line " << x << " " << t;
	LOG_WARNING << "Logging this line " << x << " " << t;
	LOG_ERROR << "Logging this line " << x << " " << t;
```
