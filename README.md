# sgetools

A few bash scripts for working with Sun Grid Engine (SGE)

- `lsfd` - list number of files within directories
- `mr` - run `more` on the most recently modified file (useful for checking logs)
- `qst` - alias for `qstat -u $USER`  which returns the status of jobs for the current user
- `qwjobs` - returns the total number of jobs submitted to the queue
- `subtemp` - creates a template submission script in the current directory
