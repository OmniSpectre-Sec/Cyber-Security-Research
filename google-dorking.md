# Google Dorking: Advanced Searching for Information Gathering

Google Dorking, also known as Google Hacking, is a technique that uses advanced operators in the Google search engine to find specific, often hidden, information that isn't available through simple keyword searches.

For a security researcher, this is a crucial skill for **Passive Reconnaissance**.

## Basic but Powerful Google Dorks:

*   **`site:`**
    *   Restricts your search to a single, specific website.
    *   **Usage:** `site:example.com admin` (This will search for the word "admin" only within the example.com website).

*   **`filetype:`**
    *   Searches for specific types of files (like PDF, Excel sheets, etc.).
    *   **Usage:** `site:example.com filetype:pdf` (This finds all PDF files hosted on the example.com website).

*   **`inurl:`**
    *   Searches for a specific word or phrase within the URL of a page.
    *   **Usage:** `inurl:login.php` (This finds pages that have "login.php" in their web address).

*   **`intitle:`**
    *   Searches for a specific word in the title of a web page.
    *   **Usage:** `intitle:"admin login"` (This finds pages that have the exact phrase "admin login" in their title).

## Combining Dorks for Powerful Results:

The real power comes from combining these operators.

**Example:**
`site:example.com filetype:xls intext:"password"`

This dork will search the `example.com` website for any Excel files (`.xls`) that also contain the word "password" somewhere in their text. You can imagine how this could reveal accidentally exposed sensitive information.

[<-- Back to Main Page](README.md)
