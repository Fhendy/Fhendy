<div align="center">

```php
<?php

class Fhendy {
    private string $role;
    private int $experience;
    private array $expertise;
    private array $tools;
    private string $mission;
    
    public function __construct() {
        $this->role = "Full-Stack Developer";
        $this->experience = 4;
        $this->expertise = ["Laravel", "Flutter", "Java", "PHP"];
        $this->tools = ["MySQL", "Git", "GitHub", "JavaScript"];
        $this->mission = "Building Digital Solutions";
    }
    
    public function getInfo(): string {
        return "Role: {$this->role} | Exp: {$this->experience} years | " .
               "Expertise: " . implode(", ", $this->expertise) . " | " .
               "Mission: {$this->mission}";
    }
}

$dev = new Fhendy();
echo $dev->getInfo();

?>
```

</div>

<div align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Poppins&size=35&color=0ea5e9&center=true&vCenter=true&width=500&lines=Tech+Stack;My+Arsenal;Skills+%26+Tools" />
</div>
