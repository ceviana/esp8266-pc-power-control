## Usage

Echo one of the supported commdns to `task.txt`.
Script `endpoint.php` will return the set value to the board on next poll
and set `OK` to `task.txt`, so the task will be passed only once.

```bash
echo -n RESET > task.txt
echo -n PWR_ON > task.txt
echo -n PWR_OFF > task.txt
echo -n SHUTDOWN > task.txt
```

ceviana.com/pc-power/endpoint.php?task=RESET

ceviana.com/pc-power/endpoint.php?task=PWR_ON 

ceviana.com/pc-power/endpoint.php?task=PWR_OFF 

ceviana.com/pc-power/endpoint.php?task=SHUTDOWN 

