# Profile

```php
<?php

class About {
  public function me($data) {
    var_dump($data);
  }
}

$data = [
  "Name" => "Hansen",
  "Proggraming Language" => ["PHP", "JAVASCRIPT"],
  "Country" => "Indonesia",
  "State" => null,
];

$AboutMe = new About();
$AboutMe->me($data);

```

Hi im **Hansen** im 11 years old im from Indonesia!

My favorite proggraming language is

```PHP```, ```JS / JAVASCRIPT```
