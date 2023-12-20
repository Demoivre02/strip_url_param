This function does the following:
Removes any duplicate query string parameters from the url
Removes any query string parameters specified within the 2nd argument (optional array)

An example:
www.saadbenn.com?a=1&b=2&a=2') // returns 'www.saadbenn.com?a=1&b=2'
