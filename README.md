# graphael-on-rails

Rails gem based on the gRaphael graphing library

http://g.raphaeljs.com/

## Installation

Add this line to your application's Gemfile:

    gem 'graphael-on-rails'

And then execute:

    $ bundle

Include assets:

    // In application.js
    //= require graphael-on-rails

## Usage

    // Creates canvas 640 × 480 at 10, 50
    var r = Raphael(10, 50, 640, 480);
    // Creates pie chart at with center at 320, 200,
    // radius 100 and data: [55, 20, 13, 32, 5, 1, 2]
    r.piechart(320, 240, 100, [55, 20, 13, 32, 5, 1, 2]);

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request

## Many Thanks

Special thanks goes to all the team who created the wonderful RaphaelJS & gRaphael libraries

http://g.raphaeljs.com/
http://raphaeljs.com/