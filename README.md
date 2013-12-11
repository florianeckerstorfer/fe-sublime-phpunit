PHPUnit Snippets for Sublime Text 2
===================================

Developed by [Florian Eckerstorfer](http://florianeckerstorfer.com) in Vienna with help from some great contributes.

- Twitter: @[Florian_](http://twitter.com/Florian_)
- App.net: @[florian](https://alpha.app.net/florian)

Installation
------------

You can install the package via Package Control. Just search for `PHPUnit Snippets`.

Alternatively you can install the package also using Git.

	cd /User/[Your User]/Library/Application\ Support/Sublime\ Text\ 2/Packages
	git clone https://github.com/florianeckerstorfer/fe-sublime-phpunit ./PHPUnit

Snippets
--------

The main part of the package are snippets. Here is a list.

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
	 * @covers [Class]::[Method]()
	 */
	public function test[Method]()
	{
		// assertions
	}

**test2**

	/**
	 * @covers [Class]::[Method1]()
	 * @covers [Class]::[Method2]()
	 */
	public function test[Method1]_[Method2]()
	{
		// assertions
	}

**testex**

	/**
	 * @covers [Class]::[Method]()
	 * @expectedException [Exception]
	 */
	public function test[Method]()
	{
		// assertions
	}

**testi**

	/**
	 * @covers [Class]::[Method]()
	 */
	public function test[Method]()
	{
	    $this->markTestIncomplete('Not yet implemented');
	}


Contributors
------------

- [Brandon Boswell](https://github.com/brandonkboswell)
- [Cyrus David](https://github.com/Apathetic012)


License
-------

The MIT License (MIT)

Copyright (c) 2012-2013 Florian Eckerstorfer

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.


[![Bitdeli Badge](https://d2weczhvl823v0.cloudfront.net/florianeckerstorfer/fe-sublime-phpunit/trend.png)](https://bitdeli.com/free "Bitdeli Badge")

