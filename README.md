### introduction ###

An simple translation tool which uses the youdao openapi,
and requires the python feature for your vim/gvim
and network for your client

### setting ###

default setting:

you can change the default setting as you like

default mapping:

    `nmap <silent> <Leader>d <Plug>DictSearch`
    --for normal mode, type <Leader>d will translate the word
    --under the cursor

    `vmap <silent> <Leader>d <Plug>DictVSearch`
    --for V mode, type <Leader>d will translate the word which
    --you have selected

    --you can change the "<Leader>d" for what you want
    --and save in your vimrc

default command:

    `command! -nargs=1 Dict call dict#Search(<q-args>)`
    --example: ':Dict hello'