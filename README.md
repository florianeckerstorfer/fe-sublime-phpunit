# PHPUnit Package for Sublime Text 2

By [Florian Eckerstorfer](http://florianeckerstorfer.com) <<florian@eckerstorfer.co>>

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

## Contributors

- [Brandon Boswell](https://github.com/brandonkboswell)
- [Cyrus David](https://github.com/Apathetic012)

## License

The MIT License (MIT)

Copyright (c) 2012-2013 Florian Eckerstorfer

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
