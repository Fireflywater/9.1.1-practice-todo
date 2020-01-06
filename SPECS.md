## Specs/Behaviors 
function `LeetspeakTranslator.Translate(stringIN)`
	Converts input string `stringIN` to leetspeak, then returns it
	Changes all instances of "e" to "3", "o" to "0", "I" (upper only) to "1", "t" to "7", and "s" to "z" unless it's the fist letter of a word.
	
	Examples:
		IN:		Translate("test")
				->
		OUT: 	"73z7"
		
		IN:		Translate("your mother is a fine woman")
				->
		OUT: 	"y0ur m07h3r iz a fin3 w0man"
		
		IN:		Translate("sSeEoOiItTsS")
				->
		OUT: 	"sz3300i177zz"