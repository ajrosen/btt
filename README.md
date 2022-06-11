# btt

Send commands to a BetterTouchTool Webserver.

https://docs.bettertouchtool.net/
https://docs.bettertouchtool.net/docs/1104_webserver.html

## Functions

- btt-customize

- btt-get-string-variable
- btt-set-string-variable
- btt-set-number-variable
- btt-trigger-named
- btt-execute-assigned-actions-for-trigger
- btt-refresh-widget
- btt-get-trigger
- btt-update-touch-bar-widget

- btt-assign-func
```emacs-lisp
 (btt-assign-func "widget" '(btt-update-text (length server-clients)))
```

- btt-assign-var
```emacs-lisp
(btt-assign-var "widget" 'battery-mode-line-string)
```

- btt-set-widget
```emacs-lisp
(btt-set-widget "widget"  (format-time-string "%b %e %l:%M %p" before-init-time))
```

- btt/major-mode
- btt/emacs-version
- btt/update-text
