Amazon MitM attack demo
=======================

### Compiling an Ettercap filter
```bash
etterfilter <input-filter-file> -o <output-file>
```

### Running an Ettercap MitM attack with a filter
```bash
ettercap -Tq -F <filter-file> -M ARP:remote /<gateway-ip>/ /<victim-ip>/
```

