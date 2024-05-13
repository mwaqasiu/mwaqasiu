## Hi there, I'm Muhammad Waqas 👋
```php
<?php

namespace MuhammadWaqas;

class About extends Me
{
  public function hireMe(): string
  {
      return 'https://www.upwork.com/freelancers/~01ed93ee301f0a4aba';
  }

  public function getBio(): string
  {
      return 'I am Muhammad Waqas, a web developer with over 8 years of experience,
              and a passion for crafting exceptional digital solutions.
              I develop modern technology web applications with popular frameworks like Laravel, Vue and React.
              SaaS,
              CMS,
              CRM
              Multi-Tenancy,
              E-Commerce,
              RestFull API
              I develop advanced software with software architectures.';
  }

  public function getMore(): array
  {
    return [
      'work' => [
        'CTO - CentoSquare (Sept 2021 - Present)',
        'Full Stack Developer - CentoSquare (Sept 2018 - Aug 2021)',
        'Lead Developer - CentoSquare (June 2017 - August 2018)',
        'Junior Web Developer - CentoSquare (April 2016 - May 2017)',
      ],
    ];
  }

  public function getCurrentState(): array
  {
    return [
      'working_on' => [
        'Laravel, Livewire, Filament, Vue.js, and React.js',
      ],
      'learning' => [
        'Advanced Programming Techniques',
        'Goo Lang',
      ],
    ];
  }

  public function getFutureGoal(): string
  {
    return 'To contribute to open source.';
  }
}
