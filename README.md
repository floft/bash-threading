Bash Threading
--------------
Multithreading in Bash really speeds some things up if you have many cores.

### Usage

    . threading # or threading_append
    thread_init

    for x; do
        your_function &
        thread_wait
    done

    thread_finish
