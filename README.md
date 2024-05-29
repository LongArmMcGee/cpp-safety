# My Presentation

This project contains an empty AsciiDoc reveal.js presentation.

## Project Structure

- `slides.adoc`: This file should contain the content of your presentation written in AsciiDoc format.
- `reveal.js/`: This directory contains the reveal.js library, which is used to render the presentation.
- `asciidoctor-reveal.js/`: This directory contains the AsciiDoctor Reveal.js extension.
- `README.md`: This file contains the documentation for the project.

## Building and Running the Presentation

To build and run the presentation, follow these steps:

1. Open the `slides.adoc` file and write your presentation content using AsciiDoc syntax.
2. Install the AsciiDoctor Reveal.js extension by running the following command:

   ```
   npm install asciidoctor-reveal.js
   ```

3. Convert the AsciiDoc file to a reveal.js presentation by running the following command:

   ```
   asciidoctor-revealjs slides.adoc
   ```

   This will generate an `slides.html` file in the same directory.

4. Open the `slides.html` file in a web browser to view the presentation.

That's it! You now have an empty AsciiDoc reveal.js presentation that can be viewed in a web browser without the need for a web server.

```

Please note that the above instructions assume that you have Node.js and npm installed on your system. If not, you will need to install them before proceeding with the installation of the AsciiDoctor Reveal.js extension.