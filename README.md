# Full setup

Some reveal.js features, like external Markdown and speaker notes, require that presentations run from a local web server. The following instructions will set up such a server as well as all of the development tasks needed to make edits to the reveal.js source code.

1. Install [Node.js](http://nodejs.org/) (4.0.0 or later) and yarn


2. Install dependencies
   ```sh
   $ yarn install
   ```

3. Serve the presentation and monitor source files for changes
   ```sh
   $ yarn start
   ```

4. Open <http://localhost:8000> to view the presentation

   You can change the port by using `yarn start -- --port=8001`.
