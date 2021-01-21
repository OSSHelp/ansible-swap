# swap

[![Build Status](https://drone.osshelp.ru/api/badges/ansible/swap/status.svg)](https://drone.osshelp.ru/ansible/swap)

Swap management (partition/file, fstab, sysctl)

## Usage (example)

```yaml
    - role: swap
```

## Available parameters

### Main

| Param | Default | Description |
| -------- | -------- | -------- |
| `swap_file_path` | `/swapfile` | Path to swap file |
| `swap_file_size_mb` | `1024` | Size of swap file in MB |
| `swap_swappiness` | `1` | Value for sysctl param vm.swappiness |

## FAQ

...

## Useful links

- [Our article](https://oss.help/kb785)

## TODO

...

## License

GPL3

## Author

OSSHelp Team, see <https://oss.help>
