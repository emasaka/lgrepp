## NAME

lgrepp - Perl implementation of [lgrep](http://www.ff.iij4u.or.jp/~nrt/lv/)

## SYNOPSIS

lgrepp [options] PATTERN [FILE...]

## DESCRIPTION

lgrepp is a Perl implementation of lgrep.

lgrepp and lgrep looks like grep, and automatically detect and convert
text encodings.

Options of lgrepp are subset of grep.

## OPTIONS

### -i, --ignore-case

ignore case distinctions

### --color=[WHEN]

use markers to highlight the matching strings.
WHEN is "always", "never", or "auto".

### -H, --with-filename

print the file name for each match.

### -n, --line-number

print line number with output lines.

### -r, -R, --recursive

read all  files  under  each  directory,  recursively.

## AUTHOR

emasaka
