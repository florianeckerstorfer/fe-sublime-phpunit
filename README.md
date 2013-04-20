# PHPUnit Package for Sublime Text 2

By [Florian Eckerstorfer](http://theroadotojoy.at) <<florian@theroadtojoy.at>>

Twitter: @[braincrafted](http://twitter.com/braincrafted)

## Installation

	cd /User/[Your User]/Library/Application\ Support/Sublime\ Text\ 2/Packages
	git clone https://github.com/florianeckerstorfer/sublime-phpunit ./PHPUnit

## Snippets

### Assertions

- **assahk** `assertArrayHasKey()`
- **assae** `assertAttributeEquals()`
- **asscha** `assertClassHasAttribute()`
- **asschsa** `assertClassHasStaticAttribute()`
- **assc** `assertContains()`
- **assco** `assertContainsOnly()`
- **asscu** `assertCount()`
- **asse** `assertEquals()`
- **assem** `assertEmpty()`
- **assexml** `assertEqualXMLStructure()`
- **assf** `assertFalse()`
- **assfe** `assertFileEquals()`
- **assfx** `assertFileExists()`
- **assgt** `assertGreatherThan()`
- **assgte** `assertGreaterThanOrEqual()`
- **assio** `assertInstanceOf()`
- **assit** `assertInternalType()`
- **asslt** `assertLessThan()`
- **asslte** `assertLessThanOrEqual()`
- **assnn** `assertNotNull()`
- **assn** `assertNull()`
- **assoha** `assertObjectHasAttribute()`
- **assre** `assertRegExp()`
- **asss** `assertSame()`
- **asssc** `assertSelectCount()`
- **assse** `assertSelectEquals()`
- **asssef** `assertStringEqualsFile()`
- **asssew** `assertStringEndsWith()`
- **asssmf** `assertStringMatchesFormat()`
- **asssmff** `assertStringMatchesFormatFile()`
- **asssre** `assertSelectRegExp()`
- **assssw** `assertStringStartsWith()`
- **asst** `assertTrue()`
- **assta** `assertTag()`
- **assxmlfef** `assertXmlFileEqualsXmlFile()`
- **assxmlsef** `assertXmlStringEqualsXmlFile()`
- **assxmlses** `assertXmlStringEqualsXmlString()`

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

**testi**

	/**
	 * [Description]
	 */
	public function test[Name]()
	{
		// assertions
		$this->markTestIncomplete('Not yet implemented');
	}
