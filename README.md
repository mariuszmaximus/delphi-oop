#This is a fork of https://bitbucket.org/soundvibe/delphi-oop. The only part of this library that I use is SvSerializer, so, at this moment this fork only deals with changes to that part of this library. I've created this fork so that SvSerializer compiles in Delphi 2010.#

# Object oriented programming for Delphi >= 2010 #

# Core #

 * *Design Patterns* - Software design patters (supports >= Delphi 2010) which uses new Delphi language features. Currently implemented patterns: Factory, Multiton, Singleton, Lazy initialization.
 * *Threading* - Futures, Parallel ForEach, Async, etc. [Threading Wiki Page]
 * *Strings* - Object oriented TSvString type. 
 * *Delegates* - implementation of multicast events [Delegates Wiki Page]
 * *Classes* - Tuples, generic Enum type, TPathBuilder.
 * *Testing* - DUnit extensions. 
 * *Logging* - wraps [http://sourceforge.net/projects/log4d/ Log4D]
 * *DB* - [SQLBuilder Dynamic SQL Builder]


# Bindings #
 * *SvBindings* - extensions to automate data binding using attributes. Requires [http://code.google.com/p/delphisorcery/ DSharp] library.
 * *MVC (Model View Controller)* pattern implementation

# Persistence #
 * *SvSerializer* - powerful serializer class which can serialize/deserialize multiple objects. Supports different backends: [http://json.org/ json] (using [https://code.google.com/p/superobject/ superobject] or DBXJSON), XML (using [http://www.simdesign.nl/forum/viewforum.php?f=2 NativeXml]), CSV.

# Web #
 * *[RESTClient1 RESTClient]* - consume RESTful web services using your own annotated class and it's methods (similar to [http://en.wikipedia.org/wiki/Java_API_for_RESTful_Web_Services JAX-RS]). Supports Google OAuth 2.0 authentication.   

_Mostly tested with Delphi XE._
