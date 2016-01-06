<a href='https://travis-ci.org/shinken-monitoring/mod-logstore-mongodb'><img src='https://api.travis-ci.org/shinken-monitoring/mod-logstore-mongodb.svg?branch=master' alt='Travis Build'></a>
mod-logstore-mongodb
====================

Shinken module for exporting logs to mongodb from the Livestatus module
The goal: Be compatible with pymongo V3

OK -->Mongo v3 open database OK (see https://github.com/shinken-monitoring/mod-logstore-mongodb/issues/16#issuecomment-169216831)

OK -->ValueError: Attempted relative import in non-package. Soluce add log_line.py

NOK --> Warning: The mod logstore-mongodb raise an exception: 'LiveStatusLogStoreMongoDB' object has no attribute 'logs_cache', I'm tagging it to restart later

You are welcome to help me
