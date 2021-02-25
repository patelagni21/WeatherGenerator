# WeatherGenerator
A weather generator produces a “synthetic” time series of weather data for a location based on
the statistical characteristics of observed weather at that location. You can think of a weather
generator as being a simulator of future weather based on observed past weather. A time series is
a collection of observations generated sequentially through time. The special feature of a time
series is that successive observations are usually expected to be dependent. In fact, this dependence
is often exploited in forecasting.

Since we are just beginning as weather forecasters, we will simplify our predictions to just
whether measurable precipitation will fall from the sky. If there is measurable precipitation,
we call it a “wet” day. Otherwise, we call it a “dry” day.
