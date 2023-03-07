# **Alla Prishchepa**
!["Alla Prishchepa long time ago"](https://avatars.githubusercontent.com/u/38905429?s=200&u=1a44734c09aa98d8a127fcd8caf3cb2482cf4f22&v=4)

### **Contact Info**
**Location:** Tbilisi, Georgia  
**Email:** tyurina.alla@gmail.com  
**GitHub:** [@allaprischepa](https://github.com/allaprischepa)  
**Drupal:** [@allaprishchepa](https://www.drupal.org/u/allaprishchepa)  
**Discord:** Alla Prishchepa (@allaprischepa)

---
### **About me**
Previously worked as PHP developer. Was a BE developer on Drupal for several years. At this moment I've decided to move to FE, thats why have started the learning journey in RS School. Hope I'll enjoy it!

---
### **Skills**
- HTML / CSS / JS (familiar with SASS, jQuery framework)
- PHP, Drupal (from v.6 to v.8), WordPress
- SQL (MySQL mostly)
- OOP
- GIT
- Linux (Ubuntu), PHPStorm
- Time-management (Jira, Readmine)
- Working in multilingual teams
- Ability to read another's code and fix bugs
- Adherence to best coding standarts

---
### **Code example**
**Sum of Digits / Digital Root** kata from Codewars:  
Given *n*, take the sum of the digits of *n*. If that value has more than one digit, continue reducing in this way until a single-digit number is produced. The input will be a non-negative integer.
```php
function digital_root($number): int
{
  switch ($number) {
    case is_int($number) && $number > 0:
      $sum = $number;
      // Split the number to array of digits.
      // Find sum until it becomes less than 10.
      while ($sum >= 10) {
        $sum = array_sum(str_split($sum));
      }
      return $sum;
    
    default:
      return 0;     
	}
}
```

---
### **Experinence**
*2013 - 2015* - [DrupalJedi](https://drupaljedi.com/), Junior/Mid Drupal Developer  
*2015 - 2020* - NDA, several freelance projects  
*2020 - 2021* - NDA, Mid Drupal Developer

---
### **Education**
2013 - Siberian State University of Telecommunications and Informatics, faculty of Mobile Radio Communication and Multimedia

---
### **Language**
- Russian (native)
- English (Intermediate level. Able to read/write/speak during teamworking)