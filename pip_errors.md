1. pip install mysqlclient
  ```
      Traceback (most recent call last):
      File "<string>", line 1, in <module>
      File "/tmp/pip-install-fs0wmmw4/mysqlclient/setup.py", line 17, in <module>
        metadata, options = get_config()
      File "/tmp/pip-install-fs0wmmw4/mysqlclient/setup_posix.py", line 44, in get_config
        libs = mysql_config("libs_r")
      File "/tmp/pip-install-fs0wmmw4/mysqlclient/setup_posix.py", line 26, in mysql_config
        raise EnvironmentError("%s not found" % (mysql_config.path,))
    OSError: mysql_config not found

    ----------------------------------------
Command "python setup.py egg_info" failed with error code 1 in /tmp/pip-install-fs0wmmw4/mysqlclient/
  ```
  ```
  sudo apt-get install libmysqlclient-dev
  ```
