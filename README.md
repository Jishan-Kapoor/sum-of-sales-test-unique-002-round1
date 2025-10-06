# Sales Summary Test

### Summary
This is a static web app that fetches data from a CSV file, calculates the total sales, and displays it on a single-page site. The title of the page is set to "Sales Summary test". Bootstrap 5 is loaded from jsdelivr for styling.

### Setup
To deploy this app on GitHub Pages:
1. Fork this repository.
2. Upload your `data.csv` file to the `/attachments` folder.
3. Enable GitHub Pages for the repository with the root directory set to `/docs`.

### Usage
You can access the page at `https://your-username.github.io/your-repo-name`. To view the sales total, you can use the query parameter `?sales=true`.

### Code Explanation
The HTML/JS code fetches the `data.csv` file, parses it to calculate the total sales, and dynamically updates the DOM to display the total in the `#total-sales` element.

### License
This project is licensed under the MIT License.