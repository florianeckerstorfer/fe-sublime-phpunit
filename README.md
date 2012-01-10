# PHPUnit Package for Sublime Text 2

By [Florian Eckerstorfer](http://theroadotojoy.at) <<florian@theroadtojoy.at>>

Twitter: @[braincrafted](http://twitter.com/braincrafted)

## Installation

	cd /User/[Your User]/Library/Application\ Support/Sublime\ Text\ 2/Packages
	git clone https://github.com/florianeckerstorfer/sublime-phpunit ./PHPUnit

## Snippets

### Assertions

- **asse** `assertEquals()`
- **assf** `assertFalse()`
- **assio** `assertInstanceOf()`
- **assnn** `assertNotNull()`
- **assn** `assertNull()`
- **asst** `assertTrue()`

### Set up and tear down

**setup**

	public function setUp()
	{
		// set up
	}

**teardown**

	public function tearDown()
	{
		// tear down
	}

### Tests

**test**

	/**
	 * [Description]
	 */
	public function test[Name]()
	{
		// assertions
	}

**testex**

	/**
	 * [Description]
	 * @expectedException [Exception]
	 */
	public function test[Name]()
	{
		// assertions
	}

