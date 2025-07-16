# Automated Job Finder & Application Bot

This project is a Python-based automation tool designed to streamline the job search and application process. It focuses on crawling company job portals (specifically Workday) to find relevant positions and, in future iterations, automatically apply to them using a provided resume.

## Features

- **Company Discovery**: Gathers a list of companies using the Workday job portal system.
- **Domain Crawler**: Crawls the web to locate the Workday domain for each company.
- **Job Search**: Searches each Workday domain using relevant keywords (e.g., "software", "engineer", "remote") to find matching job listings.
- **Future Plans**:
  - Automatically apply to jobs using stored resume and user information.
  - Support for other job platforms (e.g., Greenhouse, Lever).

## Installation

1. Clone the repository:

```bash
git clone https://github.com/yourusername/auto-job-finder.git
cd auto-job-finder
```

2. Install dependencies:

```bash
pip install -r requirements.txt
```

## Usage

The scripts in this repository currently does:
- Scrape companies that use Workday
- Discover their job portals
- Search for relevant job listings based on keywords
- Save all results into csv files.


## Notes

- This is an ongoing project. The auto-apply functionality is in development.
- For educational and personal use only.


## License

MIT License

---

Built with ❤️ to make job hunting easier.
