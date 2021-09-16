```php
<?php

namespace MrKz;

class About extends Me
{
    public function getCurrentWorkplace(): array
    {
        return [
            'workplace' => [
                'company' => 'None',
                'position' => 'Founder'         
            ]
        ];
    }

    public function getDailyKnowledge(): array
    {
        return [
            Php::class,
            Python::class,
            Aws::class,
            Shell::class,
        ];
    }

    public function getFutureGoal(): string
    {
        return 'To contribute to open source.';
    }
}
```
