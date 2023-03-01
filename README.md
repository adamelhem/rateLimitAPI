# rateLimitAPI
a Web api .net core that exposes http get and implements rate limit protection on the api. That is, we will specify that it is not possible to make more than 10 inquiries in the last 20 seconds (from the same IP address). If the same IP addresses at a higher rate - it will be blocked
