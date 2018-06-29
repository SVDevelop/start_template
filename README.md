# start_template

   pug-php-filter provides a pug php filter


    :php
        echo "hello world";
   renders:

    <?php echo "hello world"; ?>
Here's an example:
      var pug = require('pug'),
          pugPHPFilter = require('pug-php-filter');

      pug.renderFile('path/to/pug/file', {
          filters: {
              php: pugPHPFilter
          }
      });
