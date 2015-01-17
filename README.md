# json-job

The open source initiative to create a JSON-based standard for job posts. Inspired by jsonresume.org

### TODO
- [ ] From that converts to json
- [ ] json-schema
- [ ] heroku app with validation and example job API

### Install

```
git clone git@github.com:lukasz-madon/json-job.git
cd json-job
npm install
```

### Run

```foreman start```

I welcome any contributions!

```
{
  "company": "Pied Piper",
  "url": "http://piedpiper.com/",
  "remote-friendly": true,
  "market": "SaaS",
  "size": "10-50",
  "jobs": [
    {
      "position": "Software Engineer",
      "title": "Backend Developer",
      "description": "You will help us build API for our compression infrastructure.",
      "url": "http://piedpiper.com/jobs/backend-developer",
      "type": "full-time",
      "posted": "20-01-2015",
      "location": "US",
      "skills": ["Python", "Javascript", "Redis"],
      "salary-range": {
        "from": 90000,
        "to": 100000,
        "currency": "$"
      },
      "equity": {
        "from": 0.005,
        "to": 0.01
      },
      "perks": ["free food", "gym membership"],
      "apply": "http://piedpiper.com/jobs/backend-developer/apply"
    },
    {
      "position": "Software Engineer",
      "title": "Frontend Developer",
      "description": "You will help us build dashboard for our compression infrastructure.",
      "url": "http://piedpiper.com/jobs/frontend-developer",
      "type": "full-time",
      "posted": "20-01-2015",
      "location": "US",
      "skills": ["Javascript", "Angular.js", "CSS"],
      "salary-range": {
        "from": 90000,
        "to": 100000,
        "currency": "$"
      },
      "equity": {
        "from": 0.005,
        "to": 0.01
      },
      "perks": ["free food", "gym membership"],
      "apply": "http://piedpiper.com/jobs/frontend-developer/apply"
    },
    {
      "position": "UI/UX Designer",
      "title": "UX Designer",
      "description": "You will help us design dashboard for our compression infrastructure.",
      "url": "http://piedpiper.com/jobs/ux-designer",
      "type": "full-time",
      "posted": "20-01-2015",
      "location": "US",
      "skills": ["HTML", "CSS", "Photoshop"],
      "salary-range": {
        "from": 90000,
        "to": 100000,
        "currency": "$"
      },
      "equity": {
        "from": 0.005,
        "to": 0.01
      },
      "perks": ["free food", "gym membership"],
      "apply": "http://piedpiper.com/jobs/ux-designer/apply"
    }
  ]
}
```
