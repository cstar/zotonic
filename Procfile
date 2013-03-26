web: echo $PORT ; erl -env ERL_MAX_PORTS 256 +P 10000000 +K true -pa $PWD/ebin -pa  $PWD/deps/*/ebin -boot start_sasl -config $PWD/priv/erlang.config -sasl errlog_type error  -s zotonic 
