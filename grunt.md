grunt

한글


##css min @import ISSUE


I have exactly the same problem with cssmin and @import, 
and i found a solution with grunt concat:

Create a concat grunt task that:
Put @import url in the begining of mified css file and replaces references of @imports url for "".
Execute task concat:cssImport after cssmin task.
Grunt task Code: to execute (concat:cssImport)
```
 grunt.initConfig({     
   concat: {
      cssImport: {
            options: {

               process: function(src, filepath) {
                return "@import url(http://fonts.googleapis.com/css?family=Roboto:400,300,900);"+src.replace('@import url(http://fonts.googleapis.com/css?family=Roboto:400,300,900);', '');
              }
           }
         },
            files: {
                'your_location_file_origin/file.full.min.css': ['your_location_file_destination/file.full.min.css']
            }
        } )}

```

출처
https://stackoverflow.com/questions/21173522/cssmin-not-correctly-handling-import






