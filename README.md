- 👋 Hi, I’m @knetero
- 🌱 I'm currently a student at 1337khouribga.




[![abazerou's 42 stats](https://badge.mediaplus.ma/binary/abazerou)](https://github.com/oakoudad/badge42)
  
  





![knetero's GitHub stats](https://github-readme-stats.vercel.app/api?username=knetero&show_icons=true&theme=synthwave)



<?php

namespace AshBaker;

class About extends Me
{
    public function getCurrentWorkplace(): array
    {
        return [
            'workplace' => [
                'company' => 'Qquicker',
                'position' => 'Founder'         
            ]
        ];
    }

    public function getDailyKnowledge(): array
    {
        return [
            Php::class,
            Javascript::class,
            Laravel::class,
            Vuejs::class,
            Angular::class,
            ReactNative::class,
            TailwindCss::class,
            Aws::class,
        ];
    }

    public function getFutureGoal(): string
    {
        return 'To contribute to open source.';
    }
}
