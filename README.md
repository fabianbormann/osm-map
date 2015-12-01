# osm-map

An open street map element based on polymer 1.0.

## Usage

	<osm-map latitude="53.834089" longitude="10.703718" zoom="16">
		<osm-marker longitude="10.703718" latitude="53.834089" scale="0.2" image="../data/marker-blue-shadow.png"></osm-marker>
		<osm-marker longitude="10.705318" latitude="53.835789" image="../data/marker-green-icon-shadow.png"></osm-marker>
		<osm-marker longitude="10.702318" latitude="53.832789" image="../data/marker-red.png"></osm-marker>
	</osm-map>

## Dependencies

Element dependencies are managed via [Bower](http://bower.io/). You can
install that via:

    npm install -g bower

Then, go ahead and download the element's dependencies:

    bower install


## Playing With Your Element

If you wish to work on your element in isolation, we recommend that you use
[Polyserve](https://github.com/PolymerLabs/polyserve) to keep your element's
bower dependencies in line. You can install it via:

    npm install -g polyserve

And you can run it via:

    polyserve

Once running, you can preview your element at
`http://localhost:8080/components/osm-map/`, where `osm-map` is the name of the directory containing it.