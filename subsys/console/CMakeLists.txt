zephyr_sources(line_fifo.c)
zephyr_sources_ifdef(CONFIG_CONSOLE_GETCHAR tty.c getchar.c)
zephyr_sources_ifdef(CONFIG_CONSOLE_GETLINE getline.c)
