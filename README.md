# Import Logging Module

1 - Import the logging module from the script as follows:

from get_logging import logger_object
logger = logger_object()

Then every where you add print("...."), use logger.debug('Loading Dataset') / logger.info("Dataset Loaded") etc. This creates a log file, where all steps of execution i.e. the stack trace gets recorded.
Use this across all projects.
