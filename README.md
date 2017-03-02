# vim-react-snippets for Ultisnip

A set of snippets for Vim to work with Facebook's [React](http://facebook.github.io/react/)
library. This fork change the snippet syntax to ES6. Remove semicolon and comma. I also remove
snippets related to [react-classset](https://github.com/petehunt/react-classset) as it is
deprecated now.


## Dependencies

- [UltiSnips](https://github.com/SirVer/ultisnips).


## Installation

Use your preferred Vim plugin installation method. There are many plugin managers you can use for
this or go manual.

- [vundle](https://github.com/VundleVim/Vundle.vim)
- [vim-plug](https://github.com/junegunn/vim-plug)

for vundle:

````vimrc
Plugin 'SirVer/ultisnips'
Plugin 'ziyan-junaideen/vim-react-snippets'
Plugin 'honza/vim-snippets' "optional"
````

for vim-plug:

````vimrc
Plug 'SirVer/ultisnips'
Plug 'ziyan-junaideen/vim-react-snippets'
Plug 'honza/vim-snippets' "optional
````

Usage
=====

Within any Javascript or JSX file, you should be able to do the following:

(in insert mode)

```
div.<Tab>
```

expands to

```jsx
<div className="name">
</div>
```

and

```
gdp<Tab>
```

expanding to

```
getDefaultProps() {
    return {

    };
},
```

Another example:

```
rcx<Tab>
```

Expanding to

```
class ClassName extends React.Component {
  render(){
    return (

    )
  }
}
```

And a bunch of others!

Check `./UltiSnips/javascript.snippets` to see the full list.

## Thanks

This is not entirely my work, just copied existing stuff to make my life easy and will be glad if
you enjoyed.

Twitter: @ZiyanJunaideen
