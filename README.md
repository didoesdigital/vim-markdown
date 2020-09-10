# Vim Markdown

Fork of [Plasticboy's vim-markdown](https://github.com/plasticboy/vim-markdown).

## Mappings

-   `gE`: open the link under the cursor in Vim for editing. Useful for relative markdown links. `<Plug>Markdown_EditUrlUnderCursor`
-   `ge`: open the link under the cursor in Vim for editing in a new tab page or an existing tab page if there is one already.

## Task list bullet markers

Task list item prefixes are recognised as part of a bullet so hitting enter after a line starting with one of these creates a new bullet with the same task list item prefix rather than just `-`:

- `- [ ] `
- `- [x] `

See [Issue #435 · plasticboy/vim-markdown: Recognize `[ ]` as part of a bullet](https://github.com/plasticboy/vim-markdown/issues/435)

