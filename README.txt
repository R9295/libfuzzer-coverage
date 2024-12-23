NOTE: compared to fuzzbench, use -print-coverage NOT -dump-coverage  
NOTE: it will still use clang source based coverage under the hood, so it must be compiled with -fprofile-instr-generate', '-fcoverage-mapping', '-gline-tables-only

./runner -print_coverage=1 -timeout=1 -fork=1 -ignore_timeouts=1 -ignore_crashes=1 -rss_limit_mb=2048 -runs=0 <my_corpus>
cat default.profraw
