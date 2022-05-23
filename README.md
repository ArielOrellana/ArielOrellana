```php
<?php
class Person
{
 public $name;
 public $lastname;
 public $profession;

 public function __construct($name, $lastname, $profession)
 {
     $this-> name = $name;
     $this-> lastname = $lastname;
     $this-> profession = $profession;
 }
}

require_once(archivo_class);
$Ariel = new Person(name:'Ariel', lastname:'Orellana', profession: 'Developer web PHP');
echo 'Github: https://github.com/ArielOrellana';
echo 'Linkedin: https://www.linkedin.com/in/orellanaariel1998/';
echo 'Personal Web: https://arielorellana.github.io/PortfolioArielOrellana/';
?>
```
<p>Github: https://github.com/ArielOrellana
<p>Linkedin: https://www.linkedin.com/in/orellanaariel1998/</p>
<p>Personal Web: https://arielorellana.github.io/PortfolioArielOrellana/</p>
