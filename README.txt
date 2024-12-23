NOTE: compared to fuzzbench, use -print-coverage NOT -dump-coverage 

./runner -print_coverage=1 -timeout=1 -fork=1 -ignore_timeouts=1 -ignore_crashes=1 -rss_limit_mb=2048 -runs=0 <my_corpus>
