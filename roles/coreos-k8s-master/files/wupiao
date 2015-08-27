#!/bin/bash
# [w]ait [u]ntil [p]ort [i]s [a]ctually [o]pen
[ -n "$1" ] && \
  until curl -o /dev/null -sIf http://${1}; do \
    sleep 1 && echo .;
  done;
exit $?
