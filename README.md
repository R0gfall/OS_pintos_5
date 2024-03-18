# OS_pintos_5
Pintos syscalls
Реализация system calls, изменения process.c, в частности добавление дочерних процессов и работы с файловыми дескрипторами:
void halt (void)
void exit (int status)
pid_t exec (const char *cmd_line)
int wait (pid_t pid)
bool create (const char *file, unsigned initial_size)
bool remove (const char *file)
int open (const char *file)
void close (int fd)
int filesize (int fd) 
int read (int fd, void *buffer, unsigned size)
int write (int fd, const void *buffer, unsigned size)
