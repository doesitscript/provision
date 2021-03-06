drpcli params
=============

Access CLI commands relating to params

Synopsis
--------

Access CLI commands relating to params

Options
-------

::

      -h, --help   help for params

Options inherited from parent commands
--------------------------------------

::

      -d, --debug             Whether the CLI should run in debug mode
      -E, --endpoint string   The Digital Rebar Provision API endpoint to talk to (default "https://127.0.0.1:8092")
      -f, --force             When needed, attempt to force the operation - used on some update/patch calls
      -F, --format string     The serialzation we expect for output.  Can be "json" or "yaml" (default "json")
      -P, --password string   password of the Digital Rebar Provision user (default "r0cketsk8ts")
      -T, --token string      token of the Digital Rebar Provision access
      -U, --username string   Name of the Digital Rebar Provision user to talk to (default "rocketskates")

SEE ALSO
--------

-  `drpcli <drpcli.html>`__ - A CLI application for interacting with the
   DigitalRebar Provision API
-  `drpcli params create <drpcli_params_create.html>`__ - Create a new
   param with the passed-in JSON or string key
-  `drpcli params destroy <drpcli_params_destroy.html>`__ - Destroy
   param by id
-  `drpcli params exists <drpcli_params_exists.html>`__ - See if a param
   exists by id
-  `drpcli params list <drpcli_params_list.html>`__ - List all params
-  `drpcli params patch <drpcli_params_patch.html>`__ - Patch param with
   the passed-in JSON
-  `drpcli params show <drpcli_params_show.html>`__ - Show a single
   param by id
-  `drpcli params update <drpcli_params_update.html>`__ - Unsafely
   update param by id with the passed-in JSON
