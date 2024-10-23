Thank you for your interest in contributing to **HTML Snippets Pro**! Your contributions help make this extension better for everyone.

## How to Contribute

We welcome contributions that enhance the snippet collection in **HTML Snippets Pro**. Please follow the guidelines below to ensure a smooth contribution process.

### What You Can Contribute

You can contribute by adding or updating snippets in the `./snippets/snippets.json` file.

### Structure of the Snippets

Each snippet should follow the standard JSON structure. Here’s the format you should use:

```json
{
  "Snippet Name": {
    "prefix": "shortcut",
    "body": ["Your HTML code here"],
    "description": "A brief description of the snippet"
  }
}
```

- **Snippet Name**: The name of your snippet (use a unique name).
- **prefix**: The shortcut key that triggers the snippet.
- **body**: An array containing the lines of the HTML code. Each line should be a separate string.
- **description**: A short description of what the snippet does.

### Example

Here’s an example of a properly formatted snippet:

```json
{
  "Basic HTML Template": {
    "prefix": "html5",
    "body": [
      "<!DOCTYPE html>",
      "<html lang=\"en\">",
      "<head>",
      "    <meta charset=\"UTF-8\">",
      "    <meta name=\"viewport\" content=\"width=device-width, initial-scale=1.0\">",
      "    <title>${1:Document}</title>",
      "</head>",
      "<body>",
      "    ${2:Content goes here}",
      "</body>",
      "</html>"
    ],
    "description": "A basic HTML5 template."
  }
}
```

### How to Submit Your Changes

1. **Fork the Repository**: Click the "`Fork`" button on the top right of this page to create a copy of the repository in your GitHub account.
2. **Clone Your Fork**: Clone your forked repository to your local machine using the following command:
   ```bash
   git clone https://github.com/your-username/html-snippets-pro.git
   ```
3. **Make Changes**: Navigate to the `./snippets/snippets.json` file and add or update your snippets according to the structure outlined above.
4. **Commit Your Changes**: Once you have made your changes, commit them with a descriptive message:
   ```bash
   git add ./snippets/snippets.json
   git commit -m "Added new HTML snippet for XYZ"
   ```
5. **Push Your Changes**: Push your changes back to your forked repository:
   ```bash
   git push origin main
   ```
6. **Create a Pull Request**: Go to the [original repository](https://github.com/theriturajps/html-snippets-pro/) and click on the "`New Pull Request`" button. Compare your forked repository and submit your pull request with a clear description of your changes.

### Guidelines

- Ensure your snippets are well-structured and do not contain errors.
- Keep snippet names unique to avoid conflicts.
- Test your snippets in VSCode to ensure they work as expected before submitting.

Thank you for contributing to **HTML Snippets Pro**! We appreciate your help in enhancing this extension for the community.

<table>
  <tr>
    <td>
      <img src="https://github.com/theriturajps.png" width="100" style="border-radius:50%">
    </td>
    <td>
      <ul>
        <li><b>Name :</b> Ritu Raj Pratap Singh</li>
        <li><b>GitHub :</b> <a href="https://github.com/theriturajps">@theriturajps</a></li>
        <li><b>VS Code Marketplace :</b> <a href="https://marketplace.visualstudio.com/publishers/riturajps">riturajps</a></li>
      </ul>
    </td>
  </tr>
</table>
