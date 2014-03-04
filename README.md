# &lt;static-openstreetmap&gt;

`<static-openstreetmap>` is a [Polymer](http://www.polymer-project.org/) Element that displays a static map (using [OpenStreetMap](http://www.openstreetmap.org)) of
a provided address or a set of geographic coordinates.

> Maintained by [Marcin Warpechowski](https://github.com/warpech), 
[Tomek Wytrębowicz](https://github.com/tomalec).

## Usage Policy

Please note that by default we use OpenStreetMap [API](http://wiki.openstreetmap.org/wiki/Nominatim) at donated servers. So you should consider [API usage policy](http://wiki.openstreetmap.org/wiki/API_usage_policy), and [Nominatim usage policy](http://wiki.openstreetmap.org/wiki/Nominatim_usage_policy).

## Demo

> [Check it live](http://warpech.github.io/static-openstreetmap).

## Usage

1. Import Web Components' polyfill:

    ```html
    <script src="//cdnjs.cloudflare.com/ajax/libs/polymer/0.1.4/platform.js"></script>
    <script src="//cdnjs.cloudflare.com/ajax/libs/polymer/0.1.4/polymer.js"></script>
    ```

2. Import Custom Element:

    ```html
    <link rel="import" href="src/static-openstreetmap.html">
    ```

3. Start using it!

    ```html
    <static-openstreetmap></static-openstreetmap>
    ```

## Options

`query` or `lat`,`lng` set is required.

Attribute  | Options                   | Default             | Description
---        | ---                       | ---                 | ---
`query`    | *string*                  |                     | Address to search for.
`width`    | *int*                     | `500`               | Image width in px
`height`   | *int*                     | `355`               | Image height in px
`zoom`     | *int*                     | `1`                 | Zoom
`lat`      | *int*                     | `0`                 | Latitude
`lng`      | *int*                     | `0`                 | Longitude

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## History

For detailed changelog, check [Releases](https://github.com/warpech/static-openstreetmap/releases).

## License

Cusom Element is distributed under
MIT style [LICENSE](https://raw.github.com/warpech/static-openstreetmap/master/LICENSE).
Maps are provideded under [Open Database License](http://www.openstreetmap.org/copyright)  
