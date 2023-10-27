# MAC Address Changer

<p>Simple python script to change the MAC address of your NIC.</p>

## Usage

-  Navigate to file location, then run this command:

```python
python mac_changer.py --help
```

-  To change the MAC address for a specific interface use this command:

```python
python mac_changer.py -i [INTERFACE] -m [MAC ADDRESS]
```
  
-  Example case:

  ```python
python mac_changer.py -i eth0 -m 00:11:22:33:44:55
```
