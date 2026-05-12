# Prompt Redirector

A lightweight web utility that converts any text or prompt into a direct ChatGPT URL.
Users can type a prompt, launch it instantly in ChatGPT, or copy the generated URL for sharing.

---

## Features

* Generate ChatGPT prompt URLs dynamically
* Open prompts directly in a new browser tab
* Copy generated URLs to clipboard
* Simple and clean UI
* No backend required
* Works entirely in the browser

---

## Preview

```text
https://chatgpt.com/?prompt=Your%20Prompt%20Here
```

---

## How It Works

The application:

1. Reads the text entered by the user
2. Encodes the text using `encodeURIComponent()`
3. Appends it to the ChatGPT URL as a query parameter
4. Either:

   * Opens ChatGPT in a new tab
   * Copies the generated URL to clipboard

---

## Project Structure

```bash
project/
│
├── index.html
└── README.md
```

---
## Technologies Used

* HTML5
* CSS3
* Vanilla JavaScript


---

## Usage

1. Enter your prompt into the textarea
2. Click **Launch in ChatGPT** to open it directly
3. Click **Copy URL** to copy the generated link

---

## Example

Input:

```text
Explain JavaScript closures with examples
```

Generated URL:

```text
https://chatgpt.com/?prompt=Explain%20JavaScript%20closures%20with%20examples
```

---







## License

This project is open-source and available under the MIT License.
