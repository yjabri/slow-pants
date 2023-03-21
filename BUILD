python_requirements(
    name="reqs",
    module_mapping={
        "google-api-core": [
            "google.api_core",
            "google.cloud.exceptions"
        ],
        "google-cloud-bigquery-storage": [
            "google.cloud.bigquery_storage",
            "google.cloud.bigquery_storage_v1.types"
        ],
        "google-cloud-dataflow-client": [
            "google.cloud.dataflow"
        ],
    },
    overrides={
        "google-cloud-bigquery": {
            "dependencies": [
                "//:reqs#setuptools",
                "//:reqs#db-dtypes",
            ],
        },
        "google-cloud-secret-manager": {
            "dependencies": ["//:reqs#setuptools"],
        },
        "SQLAlchemy": {
            "dependencies": [
                "//:reqs#duckdb",
                "//:reqs#duckdb-engine",
                "//:reqs#sqlalchemy-bigquery",
            ]
        },
    }
)
