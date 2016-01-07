# &lt;xtag-questions&gt;

> Custom element to ask for a number and check it is the same as the answer attribute.

## Demo

[Check it live!](http://mrcinv.github.io/xtag-questions)

## Install

Install the component using [Bower](http://bower.io/):

```sh
$ bower install xtag-questions --save
```

Or [download as ZIP](https://github.com/mrcinv/xtag-questions/archive/master.zip).

## Usage

1. Import polyfill:

    ```html
    <script src="bower_components/webcomponentsjs/webcomponents.min.js"></script>
    ```

2. Import custom element:

    ```html
    <link rel="import" href="bower_components/xtag-questions/ask-number.html">
    ```

3. Start using it!

    ```html
    <ask-number correct-answer="3.1415"></ask-number>
    ```

## Options

Attribute     | Options     | Default      | Description
---           | ---         | ---          | ---
`foo`         | *string*    | `bar`        | Lorem ipsum dolor.

## Methods

Method        | Parameters   | Returns     | Description
---           | ---          | ---         | ---
`unicorn()`   | None.        | Nothing.    | Magic stuff appears.

## Events

Event         | Description
---           | ---
`onsomething` | Triggers when something happens.

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

3. Start development server and open `http://localhost:8080/components/my-repo/`.

    ```sh
    $ polyserve
    ```

## History

For detailed changelog, check [Releases](https://github.com/mrcinv/xtag-questions/releases).

## License

[MIT License](http://opensource.org/licenses/MIT)
