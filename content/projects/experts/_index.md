---
title: Experts@Minnesota
date: 2022-09-01
slug: experts
---

|||
|:----|:----|
| IT Owner | David Naughton |
| non-IT Owners | Caitlin Bakker, Jan Franzen |
| Github Repositories | [github.umn.edu](https://github.umn.edu/Libraries?q=experts&type=all&language=&sort=) |

As an example of markdown syntax highlighting, here's a snippet of Perl:

```perl
# Hash telling us which key to use if a complex frame hash is encountered
# For example, the COMM frame is complex and returns a hash with the
# following keys (with example values):
#   'Language'      => 'ENG'
#   'Description'   => 'Short Text'
#   'Text'      => 'This is the actual comment field'
#
# In this case, we want to use the "Description" to check if this is the
# correct frame.
# We always grab the "Text" for the frame data.
my %Complex_Frame_Keys =
  ( 'COMM' => 'Description', 'TXXX' => 'Description', 'UFID' => '_Data' );

# Catch interupts (SIGINT)
$SIG{INT} = \&INT_Handler;

# Set default options
my %Options = (
  skipfilename => 'flac2mp3.ignore',
  skipfile     => 1,
  processes    => $NUM_PROCESSES_DEFAULT,
  tagseparator => $TAG_SEPARATOR_DEFAULT
);

GetOptions(
  \%Options,     "quiet!",         "tagdiff",    "debug!",
  "tagsonly!",   "force!",         "usage",      "help",
  "version",     "pretend",        "skipfile!",  "skipfilename=s",
  "processes=i", "tagseparator=s", "preset=s",   "lameargs=s",
  "copyfiles"
);
```

{{< hint type=note >}}

But here's some Perl using the Hugo shortcode for better rendering. Notice the line numbers can start at any arbitrary number and the highlighting of a given line or range of lines.

{{< /hint >}}

This block uses a Hugo codeblock shortcode: 

`{{ < highlight Perl "linenos=table,linenostart=155,hl_lines=11-12 19 26-30"  >}}`


{{< highlight Perl "linenos=table,linenostart=155,hl_lines=11-12 19 26-30"  >}}
# Hash telling us which key to use if a complex frame hash is encountered
# For example, the COMM frame is complex and returns a hash with the
# following keys (with example values):
#   'Language'      => 'ENG'
#   'Description'   => 'Short Text'
#   'Text'      => 'This is the actual comment field'
#
# In this case, we want to use the "Description" to check if this is the
# correct frame.
# We always grab the "Text" for the frame data.
my %Complex_Frame_Keys =
  ( 'COMM' => 'Description', 'TXXX' => 'Description', 'UFID' => '_Data' );

# Catch interupts (SIGINT)
$SIG{INT} = \&INT_Handler;

# Set default options
my %Options = (
  skipfilename => 'flac2mp3.ignore',
  skipfile     => 1,
  processes    => $NUM_PROCESSES_DEFAULT,
  tagseparator => $TAG_SEPARATOR_DEFAULT
);

GetOptions(
  \%Options,     "quiet!",         "tagdiff",    "debug!",
  "tagsonly!",   "force!",         "usage",      "help",
  "version",     "pretend",        "skipfile!",  "skipfilename=s",
  "processes=i", "tagseparator=s", "preset=s",   "lameargs=s",
  "copyfiles"
);
{{< /highlight >}}

