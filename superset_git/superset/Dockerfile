FROM apache/superset
# Switching to root to install the required packages
USER root
# Example: installing the Postgresql driver to connect to the metadata database
RUN pip install psycopg2-binary
# Switching back to using the `superset` user
USER superset