# Unpack t.co URL

A simple script to expand Twitter's t.co links into their actual URLs.

## Installation

`brew tap adeluccar/homebrew-utilities`
`brew install unpack-tco-url`

## Usage

Pass the URL to the command:

`unpack-tco-url URL`

Or, pipe URLS into the command:

`echo "URL" | unpack-tco-url`

The possibilities are endless.

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## History

2016-06-04 v.0.2.0
2016-06-03 v.0.1.0

## Credits

Many thanks to user user495470 for his/her solution at:
http://stackoverflow.com/a/11326239/1253966

The whole script is just a fancy wrapper for that curl call.
