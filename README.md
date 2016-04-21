# d3-treemap

> Element generating the treemap

## Usage

1. Import polyfill:

    ```html
    <script src="bower_components/webcomponentsjs/webcomponents-lite.min.js"></script>
    ```

2. Import custom element:

    ```html
    <link rel="import" href="bower_components/d3-treemap/d3-treemap.html">
    ```

3. Start using it!

    ```html
    <d3-treemap></d3-treemap>
    ```

## Options

Attribute     | Options     | Default      | Description
---           | ---         | ---          | ---
`data`        | *array*     |  null        | input data for the chart

## Methods

Method                    | Parameters   | Returns     | Description
---                       | ---          | ---         | ---
`attached()`              | None.        | Nothing.    | generates chart


## Development

In order to run it locally you'll need to fetch some dependencies and a basic server setup.

1. Install [bower](http://bower.io/) & [polyserve](https://npmjs.com/polyserve):

    ```sh
    $ npm install -g bower polyserve
    ```

2. Install local dependencies:

    ```sh
    $ bower install
    ```

3. Start development server and open `http://localhost:8080/components/d3-treemap/`.

    ```sh
    $ polyserve
    ```

## History

For detailed changelog, check [Releases](https://bitbucket.org/sib-pig/d3-treemap/releases).

## License

[MIT License](http://opensource.org/licenses/MIT)
