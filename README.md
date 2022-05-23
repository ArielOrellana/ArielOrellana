<?php
class Person
{
 public $name;
 public $lastname;
 public $profession;

 public function __construct($name, $lastname, $profession)
 {
     $this-> name = $name;
     $this-> lastname = $apellido;
     $this-> profession = $profession;
 }
}

require_once(archivo_class);
$Ariel = new Person(name:'Ariel', lastname:'Orellana', profession: 'Developer web PHP');

?>
