# bashlog
Simple command line logging functions

## Usage

Source the `bashlog` file to make the logging functions available. Each takes an optional title followed by a message. For example:

```
$ . bashlog
$ e_log info "this is a message"
[info] Thu Oct 31 07:45:35 SAST 2016   this is a message
```

If the title is omitted, it defaults to `log`. Colours can be applied by using the following functions, each has the same signature as above:
- `e_log` (default foreground colour, usually white)
- `e_red`
- `e_green`
- `e_yellow`
- `e_blue`
- `e_magenta`
- `e_cyan`
- `e_warn` (same as `e_yellow`)
- `e_error` (same as `e_red`)

