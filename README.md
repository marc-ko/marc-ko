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
                'position' => 'Junior Full Stack Web Developer'         
            ]
        ];
    }

    public function getMoreInfo()
    {

        languages = [
            Php::class,
            'JavaScript' =>
                [
                Javascript::class,
                Vuejs::class // Beginner Level
                ],
            Python::Class
            Dart::Class // Beginner Level (Flutter)
            Cpp::Class // Beginner Level
            Solidity::Class // Beginner Level


        ];
        frameworks = [
            Laravel::class,
            Codeigniter::class, 
        ];
        return languages, frameworks;
    }

    public function getMyContact()
    {
        email = "marcoko@ckentgroup.com";
        website = "marcoko.com";
        linkedin = "https://www.linkedin.com/in/ka-chun-ko-1733a8224/";
        
        return email, website, linkedin;
    }

    public function getFutureGoal()
    {
        return 'To be an all-rounded and versatile person 😉.';
    }
}
?>
```
