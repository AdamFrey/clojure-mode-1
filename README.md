# codemirror-clojure

Live demo: https://nextjournal.github.io/codemirror.next-clojure/

dev: `shadow-cljs watch app`

----

In progress:


Next:
- [ ] Copy/paste (only first line copies to clipboard?)
- [ ] "Yank" after kill (https://www.howtogeek.com/293850/how-to-use-macos-built-in-kill-and-yank-as-an-alternative-cut-and-paste/)
- [ ] Ctrl-A => move to beginning of line (first non-whitespace char)


Done

- [x] Expand/contract region
- [x] Barf
- [x] Slurp
- [x] Format whitespace (necessary for commands like Slurp to behave nicely)
- [x] Navigate left/right by sexp
- [x] cannot 'indent-all', changes on one line don't affect measurements taken on subsequent lines
- [x] operators are recognized (lists with symbol in 1st position)
- [x] Unwrap current collection
- [x] Kill (remove all children of current node starting on current line)
- [x] GitHub Action to publish demo site to github.io
- [x] indentation
- [x] odd error recovery behaviour - a `#` token can't be deleted
- [x] deletion
