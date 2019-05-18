# CSS3 Accordion
Design and build an accordion using CSS3 features.

### Understand CSS3
##### CSS Selectors
Selectors are one of, if not, the most important parts of CSS. They shape the cascade and determine how styles are to be applied to elements on a page. CSS3 brought new selectors, opening a whole new world of opportunities and improvements to existing practices. Here we’ll discuss selectors, old and new, and how to best put them to use.

##### Common Selectors

**Type Selector** : Selects an element by its type. 

Example : ```h1```

**Class Selector** : Selects an element by the class attribute value, which may be reused multiple times per page. 

Example : ```.tagline```

**ID Selector** : Selects an element by the ID attribute value, which is unique and to only be used once per page. 

Example : ```#intro```

##### Child Selectors

**Descendant Selector** :	Selects an element that resides anywhere within an identified ancestor element.

Example : ```article h2```

**Direct Child Selector** :	Selects an element that resides immediately inside an identified parent element.

Example : ```article > p```

##### Sibling Selectors

**General Sibling Selector** :	Selects an element that follows anywhere after the prior element, in which both elements share the same parent.

Example : ```h2 ~ p```

**Adjacent Sibling Selector** :	Selects an element that follows directly after the prior element, in which both elements share the same parent.

Example : ```h2 + p```

## Attribute Selectors

**Attribute Present Selector** :	Selects an element if the given attribute is present.

Example : ```a[target]```

**Attribute Equals Selector** :	Selects an element if the given attribute value exactly matches the value stated.

Example : ```a[href="http://google.com/"]```

**Attribute Contains Selector** :	Selects an element if the given attribute value contains at least once instance of the value stated.

Example : ```a[href*="login"]```

**Attribute Begins With Selector** :	Selects an element if the given attribute value begins with the value stated.

Example : ```a[href^="https://"]```

**Attribute Ends With Selector** :	Selects an element if the given attribute value ends with the value stated.

Example : ```a[href$=".pdf"]```

**Attribute Spaced Selector** :	Selects an element if the given attribute value is whitespace-separated with one word being exactly as stated.

Example : ```a[rel~="tag"]```

**Attribute Hyphenated Selector** :	Selects an element if the given attribute value is hyphen-separated and begins with the word stated.

Example : ```a[lang|="en"]```
