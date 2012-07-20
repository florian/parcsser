parCSSer
========

# Parser output [draft]

```ruby
{

  'at-rules' => {

    'charset' => '',

    'media' => [
      { 'conditions' => [], 'rules' => {} },
    ],

    'import' => [
      { 'url' => '', 'conditions': [] }
    ],

    'page': [
      { 'selector' => '', 'rules' => {} }
    ],

    'font-face': [
      { rules => {} }
    ],

    'namespace' => [], # ?

    'keyframe' => [
      { 'name' => '', 'rules' => {} }
    ]

  },

  'rules' => {

    'key:selector' => {
      'property' => 'value'
    }

  }

}
```

Parsing `h1 { color: red; }` should return a `rules` hash:

```ruby
{
  'h1' => {
		'color' = 'red'
	}
}
```