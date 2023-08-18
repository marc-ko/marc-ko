```php
<?php

namespace Marcooko;

class About extends Me
{
    public function getCurrentWorkplace()
    {
        return [
            'workplace' => [
                'company' => 'C Kent Group',
                'position' => 'Junior Full Stack Developer'         
            ]
        ];
    }

    public function getMoreInfo()
    {

        languages = [
            Php::class,
            [// JavaScript
            Javascript::class,
            Vuejs::class, // Beginner Level
            ],
            Dart::Class // Beginner Level (Flutter)
            Cpp::Class // Beginner Level

        ];
        frameworks = [
            Laravel::class,
            Codeigniter::class, 
        ];
        return languages, frameworks;
    }

    public function getFutureGoal()
    {
        return 'To improve my programming skill better.';
    }
}
```
