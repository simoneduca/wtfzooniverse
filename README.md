# WTF Engine

Inspired by [wtfnasa.com](http://wtfnasa.com/) and built with [WTFEngine](https://github.com/soulwire/WTFEngine), this little website will tell you all the things the Zooniverse has done to make your life awesome!

## How to use it

You can populate it using one of three different methods. Each is controlled from [`main.js`](https://github.com/soulwire/WTFEngine/blob/master/scripts/main.js) (where you will find commented examples of each technique.)

1. JavaScript Object literal
2. A JSON file
3. A live feed from a Google spreadsheet

If you choose to use a Google spreadsheet, you must publish it first and be sure to manually republish it after editing if you want changes to propagate immediately, otherwise they will take around 15 minutes.

## Example
```json
{
    template: [ "Big @color @animal", "Silly @animal with @color fur" ],
    animal: [ "dog", "cat", "rabbit" ],
    color: [ "red", "blue", "green", "yellow" ]
};
```

