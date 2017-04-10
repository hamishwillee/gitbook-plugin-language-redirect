# gitbook-plugin-language-redirect

Creates a redirect from the root for every page in the specified language. 

This is useful if you're migrating from a single-language to a mulit-language system and want to redirect URLs to that language.


## Installation

Add this to your **book.json** plugin list:

```
{
    "plugins": [ 
       "language-redirect@git+https://github.com/hamishwillee/gitbook-plugin-default-language-redirect.git" 
       ]
}
```

## Usage

Configuration for this plugin is specified in book.json in the *pluginsConfig* object, with the key language-redirect. At this time the only configuration variable is the language, which will default to 'en':

```
"pluginsConfig": {
    "language-redirect": {
        "language": "en"
    }
}
```
