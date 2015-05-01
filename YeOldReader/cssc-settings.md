{
	"format": "max",

	// Compresses individual units in calc function, and removes whitespace
	"Calc Units": true,

	// Removes unecessary trailing zeroes from values
	"Trailing Zeroes": true,

	// Removes unecessary leading zeroes from values
	"Leading Zeroes": true,

	// Removes unecessary suffix from zero unit values
	"Unit Suffix": true,

	// Compressing rect shape declarations
	"Rect Shape": true,

	// Breaks down gradient properties and runs compressions on individual parts
	"Gradient Compression": true,

	// Converts RGBA to RGB when opacity is 1
	"RGBA to RGB": true,

	// Converts HSLA to HSL when opacity is 1
	"HSLA to HSL": true,

	// Converts RGB to Hex code
	"RGB to Hex": true,

	// Converts HSL to Hex code
	"HSL to Hex": true,

	// Converts colors to shorter hex representation
	"Color to Hex": true,

	// Converts hex codes to short color names
	"Hex to Color": true,

	// Converts hex codes to short safe color names
	"Hex to Safe Color": true,

	// Converts long hex to short hex
	"Shrink Hex": true,

	// Lowercases hex color values for better gzip compression
	"Lowercase Hex": false,

	// Converts element selectors to lowercase
	"Lowercase Selectors": false,

	// Remove attribute quotes when they are not needed
	"Trim Selector Attribute Quotes": true,

	// Converts id attributes to id selectors
	"ID Attribute to Selector": true,

	// Converts class attributes to class selectors
	"Class Attribute to Selector": true,

	// Removes entire selector before last ID selector
	"Strict ID": false,

	// Removes repeated selectors separated by commas
	"Comma Repeats": true,

	// Converts font weight strings to their numeric counterparts
	"Font Weight Conversion": true,

	// Removes quotes around font family names
	"Font Family Quotes": true,

	// Combines font declarations into single property
	"Font Combinations": true,

	// General whitespace removal and unit compression of css functions
	"Function Units": true,

	// Converts none values to zeroes for allowed properties
	"None Conversions": true,

	// Removes quotes around url wrappers
	"URL Trim": true,

	// Converts at-rule one liner url's to strings
	"Atrule URL Trim": true,

	// Combines Margin/Padding shorthand directionals
	"Margin, Padding Shorthand": true,

	// Combines margin and padding directionals into their shorter alternative
	"Margin, Padding Combinations": true,

	// Converts shorthand border radius properties
	"Border Radius Shorthand": true,

	// Combines border radius directionals into their shorter alternative
	"Border Radius Combinations": true,

	// Combine border & outline expanded properties into shorthand
	"Border, Outline Style Combinations": true,

	// Combines border directionals into single border property
	"Border Combinations": true,

	// Combines list-style properties into their shorter alternative
	"List Style Combinations": true,

	// Lowercases property names for better chance at compression during gzip
	"Lowercase Properties": true,

	// Sorts property-values for a better chance at compression during gzip
	"Sort Properties": true,

	// Sorts comma separated selectors for a better chance at compression during gzip
	"Sort Multi Selectors": true,

	// Moves charset and import declarations to the top of the stylesheet (to help with concatenation)
	"Order Atrules": true,

	// Combines rule sets with matching selectors
	"Common Selectors": true,

	// Combines rule sets with matching rules
	"Common Rules": true,

	// Removes multiply defined properties
	"Duplicate Properties": true,

	// Removes properties that don't have values.
	"Empty Values": true,

	// Removes all comments from style sheet, with the exception of comments that are prefixed with a bang '/*!'
	"Strip Comments": false,

	// Removes all branches with no rules
	"Strip Empty Branches": true
}