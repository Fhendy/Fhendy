<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0ea5e9,0284c7,0369a1,1e40af&height=300&section=header&text=Fhendy%20-%20Fh%20Digital&fontSize=55&fontColor=fff&animation=twinkling&fontAlignY=35&desc=Full-Stack%20Developer%20%7C%20Digital%20Solution%20Architect&descAlignY=55&descAlign=50" />
</div>

<div align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Poppins&size=30&duration=1500&pause=300&color=0ea5e9&center=true&vCenter=true&width=800&lines=+Full-Stack+Developer;+Laravel+Specialist;+Flutter+Mobile+Developer;+Java+Expert;+PHP+Master;+Digital+Solution+Architect;+Building+Scalable+Systems;+Code+Architect;+Problem+Solver;+Innovation+Master" />
</div>

<div align="center">
  <img width="100%" src="https://github.com/platane/snk/raw/output/github-contribution-grid-snake-dark.svg" />
</div>

<div align="center">
  <img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%" height="3">
</div>

<div align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Poppins&size=35&duration=2000&pause=500&color=0ea5e9&center=true&vCenter=true&width=400&lines=+About+Me;+Who+Am+I%3F;+Meet+Fhendy" />
</div>

<div align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=18&duration=2500&pause=800&color=0284c7&center=true&vCenter=true&width=700&lines=struct+Fhendy+%7B;++++role%3A+%26'static+str%2C;++++experience%3A+u8%2C;++++expertise%3A+Vec%3C%26'static+str%3E%2C;++++tools%3A+Vec%3C%26'static+str%3E%2C;++++mission%3A+%26'static+str%2C;%7D;fn+main()+%7B;++++let+dev+%3D+Fhendy+%7B;+++++++role%3A+%22+Full-Stack+Developer%22%2C;+++++++experience%3A+4%2C;+++++++expertise%3A+vec!%5B%22+Laravel%22%2C+%22+Flutter%22%2C+%22+Java%22%2C+%22+PHP%22%5D%2C;+++++++tools%3A+vec!%5B%22+MySQL%22%2C+%22+Git%22%2C+%22+JavaScript%22%5D%2C;+++++++mission%3A+%22+Building+Digital+Solutions%22%2C;++++%7D%3B;++++println!(%22+%7B%3A%23%3F%7D+%22%2C+dev)%3B;%7D" />
</div>

<div align="center">
  <img src="https://user-images.githubusercontent.com/74038190/212284100-561aa473-3905-4a80-b561-0d28506553ee.gif" width="900">
</div>

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
