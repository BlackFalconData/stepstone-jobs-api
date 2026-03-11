# StepStone Jobs API

Search job listings from StepStone, TotalJobs and related job boards via a developer-friendly API.

Powered by the Apify actor:
https://apify.com/blackfalcondata/stepstone-jobs-feed

## Example request

Run the actor via the Apify API:

POST https://api.apify.com/v2/acts/blackfalcondata~stepstone-jobs-feed/runs

Example input:

{
  "query": "data engineer",
  "geo": "DE",
  "maxResults": 10
}

## Example response

{
  "count": 10,
  "results": [
    {
      "title": "Senior Data Engineer",
      "company": "Siemens AG",
      "location": "Munich, Bavaria",
      "datePosted": "2026-03-07T01:19:42+01:00"
    }
  ]
}

## Supported portals

- stepstone.de
- stepstone.at
- stepstone.be
- stepstone.nl
- totaljobs.com
- cwjobs.co.uk
- jobsite.co.uk
- milkround.com
- careerstructure.com
- cityjobs.com
- caterer.com
- pnet.co.za
- jobs.ie

## API

Full documentation and usage examples:

https://apify.com/blackfalcondata/stepstone-jobs-feed
