# Process Monitoring

This section documents process and resource monitoring performed across Linux and Windows Server.

The objective was to compare how both operating systems expose running processes, resource consumption, and process identifiers, while also practicing process termination from the command line.

## Linux Monitoring

Ubuntu Server was monitored using the `top` command.

This allowed observation of:

- Running processes
- Process IDs (PID)
- CPU usage
- Memory usage
- Process state
- System activity in real time

The exercise also included terminating a selected process using:

```bash
sudo kill -9 <PID>
