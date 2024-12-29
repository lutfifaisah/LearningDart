1. UpperCamelCase names capitalize the first letter of each word, including the first.

   ex. Classes, enum types, typedefs, extensions, type parameters, 

2. lowerCamelCase names capitalize the first letter of each word, except the first which is always   
   lowercase, even if it's an acronym.

   ex. identifiers (object class, variable), constant names, 

3. lowercase_with_underscores names use only lowercase letters, even for acronyms, and separate words 
   with _.

   ex. filename, folder, import prefixes, 

4. capitalize acronyms 'ID' , 'TV'

5. dart: imports before other imports
   ex. 
   import 'dart:async';
   import 'dart:html';

   import 'package:bar/bar.dart'; 
   import 'package:foo/foo.dart';  

6.  imports before relative imports
    ex.
    import 'package:bar/bar.dart';
    import 'package:foo/foo.dart';

    import 'util.dart';

7.  exports in a separate section after all imports (import first then exports)


