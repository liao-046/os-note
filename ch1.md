# OS ch1 筆記整理

## ainframe Systems (大型主機系統: 任務性質單純、大量處理資料)
<span style="color: red;">### Batch (批次系統: 一次一批自動處理)</span>
- user submit jobs
- Operator sort jobs
- process one job at a time

- Drawbacks:
    - One job at a time 
    - No interaction
    - CPU idle 

### Muti-programming (做完才讓出CPU)
- OS task:
    - memory management
    - CPU scheduling
    - I/O system
### Time-sharing (Multi-tasking system: time slot)
- interactive system
- multi users share the computer simultaneously
- switch job:
    - finish
    - waiting I/O
    - a short period of time

- OS task:
    - virtual memory
    - file system / disk management
    - process synchronization / deadlock

![Mainframe system summary](images/os_1.png)
## Computer-system architecture  
## Special-purpose Systems


