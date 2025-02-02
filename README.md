# schlapphut

`schlapphut` scrapes the
[JSON endpoint of all job listings](https://apply.intelligencecareers.gov/job-listings/search)
posted on
[apply.intelligencecareers.gov](https://apply.intelligencecareers.gov/)
and commits the result to this repository if there is a difference.

**Edit from 2025-02-02:** Since 2025-01-31 the JSON endpoint stopped working.
First, HTTP 503 Error codes were thrown on `apply.intelligencecareers.gov`, then it said:
"We are currently experiencing technical issues that are preventing us from accepting new applications. Our team is working to resolve the problem as soon as possible."

Meanwhile `www.intelligencecareers.gov` links to [intelligencecareers.usajobs.gov](https://intelligencecareers.usajobs.gov/), presenting a whole new form to submit applications.
This new form is not so easy to scrape, because it misses an endpoint, that exposes all data.
You'd need to iterate over all pages with the results.

Thus, this project is ended and archived for now.
