```php
<?php

namespace DanonekTM;

class About extends Me
{
	public function getStack()
	{
		return
		[
			"languages" => ["PHP", "Java", "Javascript", "Python"],
			"misc_lang" => ["HTML", "Markdown", "BBCode"],
			"stylesheets" => ["CSS", "SCSS", "SASS"],
			"operating_systems" => ["Windows", "Linux", "FreeBSD"],
			"databases" => ["MySQL", "SQLite", "PostgreSQL"],
			"dev_ops" => ["Azure", "GCP", "Docker", "Git"],
			"learning" => ["C", "C++", "Python"]
		];
	}
}
?>
```
