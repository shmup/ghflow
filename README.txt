GHFLOW(1)                        User Commands                        GHFLOW(1)

NAME
      ghflow - create and submit a new GitHub Pull Request

SYNOPSIS
      Add ghflow to your $PATH and make sure you have urwid installed.

      ghflow [OPTIONS]

DESCRIPTION
      This utility provides a simple terminal-based interface to create
      and submit a new GitHub Pull Request. The user can choose the branch
      type, enter the PR title and body, and the script will automatically
      generate the branch name, perform the necessary git actions, and open
      the PR in the browser.

OPTIONS
      -d, --dry-run     perform a dry run and just print the commands

EXAMPLES
      ghflow
      ghflow --dry-run

AUTHOR
      Jared Tyler Miller <jared@smell.flowers>

LICENSE
      This software is released under the Zero-Clause BSD License.

      SPDX-License-Identifier: 0BSD

      Permission to use, copy, modify, and/or distribute this software for any
      purpose with or without fee is hereby granted.

      THE SOFTWARE IS PROVIDED "AS IS" AND THE AUTHOR DISCLAIMS ALL WARRANTIES
      WITH REGARD TO THIS SOFTWARE INCLUDING ALL IMPLIED WARRANTIES OF
      MERCHANTABILITY AND FITNESS. IN NO EVENT SHALL THE AUTHOR BE LIABLE FOR
      ANY SPECIAL, DIRECT, INDIRECT, OR CONSEQUENTIAL DAMAGES OR ANY DAMAGES
      WHATSOEVER RESULTING FROM LOSS OF USE, DATA OR PROFITS, WHETHER IN AN
      ACTION OF CONTRACT, NEGLIGENCE OR OTHER TORTIOUS ACTION, ARISING OUT OF
      OR IN CONNECTION WITH THE USE OR PERFORMANCE OF THIS SOFTWARE.

GITHUB
      https://github.com/shmup/ghflow
