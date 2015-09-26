# angular-snippets

Clone this repo into your sublime user folder. Type the trigger(e.g. a-fact) and press tab to create the snippet. Use tab to edit the next field.

Linux: ~/.config/sublime-text-3/Packages/User

Mac: ~/Library/Application Support/Sublime Text 3/Packages/User

Windows: Users/<NAME>/AppData/Roaming/Sublime Text 3/Packages/User

```
a-app

angular.module('app', ['']);
```

```
a-ctrl

(function() {
  'use strict';

  angular.module('app')
  .controller('<Name>Ctrl', <name>Ctrl);

  function <name>Ctrl() {
    var self = this;

    
  }

})();
```

```
a-fact

(function() {
  'use strict';

  angular.module('app')
  .factory('<name>Factory', <name>Factory);

  function <name>Factory() {
    var services = {
      <function name>: <function name>
    };

    return services;

    function <function name>() {
      
    }
  }

})();
```

```
a-dir

(function() {
  'use strict';

  angular.module('app')
  .directive('<name>', <name>);

  function <name>() {
    var directive = {
      template: '',
      link: link
    };

    return directive;

    function link(scope, elem, attrs) {
      
    }
  }

})();
```