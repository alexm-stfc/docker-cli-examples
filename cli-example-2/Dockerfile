FROM python:3

COPY . /context
RUN pip install /context

ENTRYPOINT ["python", "-m", "cli_example"]
