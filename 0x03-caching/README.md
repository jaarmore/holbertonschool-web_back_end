# 0x03. Caching

## Requirements

+ All your files will be interpreted/compiled on `Ubuntu 18.04` LTS using `python3` (version 3.7)
+ All your files should end with a new line
+ The first line of all your files should be exactly `#!/usr/bin/env python3`
+ A `README.md` file, at the root of the folder of the project, is mandatory
+ Your code should use the `pycodestyle` style (version 2.5)
+ All your files must be executable
+ The length of your files will be tested using `wc`

### More Info

Parent class `BaseCaching`

```py
$ cat base_caching.py
#!/usr/bin/python3
""" BaseCaching module
"""

class BaseCaching():
    """ BaseCaching defines:
      - constants of your caching system
      - where your data are stored (in a dictionary)
    """
    MAX_ITEMS = 4

    def __init__(self):
        """ Initiliaze
        """
        self.cache_data = {}

    def print_cache(self):
        """ Print the cache
        """
        print("Current cache:")
        for key in sorted(self.cache_data.keys()):
            print("{}: {}".format(key, self.cache_data.get(key)))

    def put(self, key, item):
        """ Add an item in the cache
        """
        raise NotImplementedError("put must be implemented in your cache class")

    def get(self, key):
        """ Get an item by key
        """
        raise NotImplementedError("get must be implemented in your cache class")
```

## Tasks

0. Basic dictionary
1. FIFO caching
2. LIFO Caching
3. LRU Caching
4. MRU Caching
5. LFU Caching

## AUTHOR

### JACKSON MORENO
