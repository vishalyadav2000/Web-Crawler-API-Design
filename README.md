# Web-Crawler-API-Design
Parameters:

root_url (string): The starting URL to begin crawling.

depth (integer): The maximum depth to crawl (how many levels of links to follow).

Response Fields:

root_url: The root webpage provided as input.

depth: The depth limit requested.

crawled_links: A list of objects representing crawled URLs, each containing:

url: The crawled page.

depth: The depth at which this page was found.

links: Links found on this page.
