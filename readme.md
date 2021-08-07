# fetch timeout

## Notes

If you are concerned with the stability of your api adding a little extra logic to fetch can help.
Adding an AbortController and a few retries with exponential backoff can sometimes be useful.
