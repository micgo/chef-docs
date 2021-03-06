.. The contents of this file are included in multiple topics.
.. This file should not be changed in a way that hinders its ability to appear in multiple documentation sets.

The |service rabbitmq| service has the following settings:

.. list-table::
   :widths: 200 300
   :header-rows: 1

   * - Setting
     - Description
   * - ``rabbitmq['consumer_id']``
     - Default value: ``"hotsauce"``.
   * - ``rabbitmq['data_dir']``
     - Default value: ``"/var/opt/opscode/rabbitmq/db"``.
   * - ``rabbitmq['dir']``
     - Default value: ``"/var/opt/opscode/rabbitmq"``.
   * - ``rabbitmq['enable']``
     - |enable service| Default value: ``true``.
   * - ``rabbitmq['ha']``
     - |use ha| Default value: ``false``.
   * - ``rabbitmq['jobs_password']``
     - Default value: ``"workcomplete"``.
   * - ``rabbitmq['jobs_user']``
     - Default value: ``"jobs"``.
   * - ``rabbitmq['jobs_vhost']``
     - Default value: ``"/jobs"``.
   * - ``rabbitmq['log_directory']``
     - |directory logs| The default value is the recommended value. Default value: ``"/var/log/opscode/rabbitmq"``.
   * - ``rabbitmq['log_rotation']``
     - |log_rotation| Default value: ``{ 'file_maxbytes' => 104857600, 'num_to_keep' => 10 }``
   * - ``rabbitmq['node_ip_address']``
     - |ip_address rabbitmq| Default value: ``"127.0.0.1"``.
   * - ``rabbitmq['node_port']``
     - |port rabbitmq| Default value: ``"5672"``.
   * - ``rabbitmq['nodename']``
     - |name node| Default value: ``"rabbit@localhost"``.
   * - ``rabbitmq['password']``
     - |password rabbitmq| Default value: ``"chefrocks"``.
   * - ``rabbitmq['reindexer_vhost']``
     - Default value: ``"/reindexer"``.
   * - ``rabbitmq['user']``
     - Default value: ``"chef"``.
   * - ``rabbitmq['vhost']``
     - Default value: ``"/chef"``.
   * - ``rabbitmq['vip']``
     - |ip_address virtual| Default value: ``"127.0.0.1"``.

