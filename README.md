modified after blog: https://levelup.gitconnected.com/inter-process-communication-between-node-js-and-python-2e9c4fda928d

Added extra support for nodejs process waiting for pipe_a to be created by python3, so that the starting order of two processes won't matter. You can execute `node fofo_writer.js` and `python3 fifo_reader.py` in either order on two terminals.