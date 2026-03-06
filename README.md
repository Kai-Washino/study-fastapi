# FastAPI 公式ドキュメント 写経・学習ノート

FastAPI 公式ドキュメント (https://fastapi.tiangolo.com/) を読みながら、コードを写経して学ぶためのリポジトリです。
フォルダ構成は公式ドキュメントの章立てに対応しています。

---

## フォルダ構成

```
study-fastapi/
├── 01_tutorial/          # Tutorial - User Guide
├── 02_advanced/          # Advanced User Guide
├── 03_deployment/        # Deployment
└── 04_how_to/            # How To - Recipes
```

---

## 01_tutorial — Tutorial - User Guide

公式ドキュメント: https://fastapi.tiangolo.com/tutorial/

| フォルダ | 対応ドキュメント |
|---|---|
| `01_first_steps/` | [First Steps](https://fastapi.tiangolo.com/tutorial/first-steps/) |
| `02_path_parameters/` | [Path Parameters](https://fastapi.tiangolo.com/tutorial/path-params/) |
| `03_query_parameters/` | [Query Parameters](https://fastapi.tiangolo.com/tutorial/query-params/) |
| `04_request_body/` | [Request Body](https://fastapi.tiangolo.com/tutorial/body/) |
| `05_query_parameters_and_string_validations/` | [Query Parameters and String Validations](https://fastapi.tiangolo.com/tutorial/query-params-str-validations/) |
| `06_path_parameters_and_numeric_validations/` | [Path Parameters and Numeric Validations](https://fastapi.tiangolo.com/tutorial/path-params-numeric-validations/) |
| `07_query_parameter_models/` | [Query Parameter Models](https://fastapi.tiangolo.com/tutorial/query-param-models/) |
| `08_body_multiple_parameters/` | [Body - Multiple Parameters](https://fastapi.tiangolo.com/tutorial/body-multiple-params/) |
| `09_body_fields/` | [Body - Fields](https://fastapi.tiangolo.com/tutorial/body-fields/) |
| `10_body_nested_models/` | [Body - Nested Models](https://fastapi.tiangolo.com/tutorial/body-nested-models/) |
| `11_declare_request_example_data/` | [Declare Request Example Data](https://fastapi.tiangolo.com/tutorial/schema-extra-example/) |
| `12_extra_data_types/` | [Extra Data Types](https://fastapi.tiangolo.com/tutorial/extra-data-types/) |
| `13_cookie_parameters/` | [Cookie Parameters](https://fastapi.tiangolo.com/tutorial/cookie-params/) |
| `14_header_parameters/` | [Header Parameters](https://fastapi.tiangolo.com/tutorial/header-params/) |
| `15_cookie_parameter_models/` | [Cookie Parameter Models](https://fastapi.tiangolo.com/tutorial/cookie-param-models/) |
| `16_header_parameter_models/` | [Header Parameter Models](https://fastapi.tiangolo.com/tutorial/header-param-models/) |
| `17_response_model_return_type/` | [Response Model - Return Type](https://fastapi.tiangolo.com/tutorial/response-model/) |
| `18_extra_models/` | [Extra Models](https://fastapi.tiangolo.com/tutorial/extra-models/) |
| `19_response_status_code/` | [Response Status Code](https://fastapi.tiangolo.com/tutorial/response-status-code/) |
| `20_form_data/` | [Form Data](https://fastapi.tiangolo.com/tutorial/request-forms/) |
| `21_form_models/` | [Form Models](https://fastapi.tiangolo.com/tutorial/request-form-models/) |
| `22_request_files/` | [Request Files](https://fastapi.tiangolo.com/tutorial/request-files/) |
| `23_request_forms_and_files/` | [Request Forms and Files](https://fastapi.tiangolo.com/tutorial/request-forms-and-files/) |
| `24_handling_errors/` | [Handling Errors](https://fastapi.tiangolo.com/tutorial/handling-errors/) |
| `25_path_operation_configuration/` | [Path Operation Configuration](https://fastapi.tiangolo.com/tutorial/path-operation-configuration/) |
| `26_json_compatible_encoder/` | [JSON Compatible Encoder](https://fastapi.tiangolo.com/tutorial/encoder/) |
| `27_body_updates/` | [Body - Updates](https://fastapi.tiangolo.com/tutorial/body-updates/) |
| `28_dependencies/` | **Dependencies** |
| `28_dependencies/01_classes_as_dependencies/` | [Classes as Dependencies](https://fastapi.tiangolo.com/tutorial/dependencies/classes-as-dependencies/) |
| `28_dependencies/02_sub_dependencies/` | [Sub-dependencies](https://fastapi.tiangolo.com/tutorial/dependencies/sub-dependencies/) |
| `28_dependencies/03_dependencies_in_path_operation_decorators/` | [Dependencies in path operation decorators](https://fastapi.tiangolo.com/tutorial/dependencies/dependencies-in-path-operation-decorators/) |
| `28_dependencies/04_global_dependencies/` | [Global Dependencies](https://fastapi.tiangolo.com/tutorial/dependencies/global-dependencies/) |
| `28_dependencies/05_dependencies_with_yield/` | [Dependencies with yield](https://fastapi.tiangolo.com/tutorial/dependencies/dependencies-with-yield/) |
| `29_security/` | **Security** |
| `29_security/01_security_first_steps/` | [Security - First Steps](https://fastapi.tiangolo.com/tutorial/security/first-steps/) |
| `29_security/02_get_current_user/` | [Get Current User](https://fastapi.tiangolo.com/tutorial/security/get-current-user/) |
| `29_security/03_simple_oauth2_with_password_and_bearer/` | [Simple OAuth2 with Password and Bearer](https://fastapi.tiangolo.com/tutorial/security/simple-oauth2/) |
| `29_security/04_oauth2_with_password_hashing_and_jwt/` | [OAuth2 with Password (and hashing), Bearer with JWT tokens](https://fastapi.tiangolo.com/tutorial/security/oauth2-jwt/) |
| `30_middleware/` | [Middleware](https://fastapi.tiangolo.com/tutorial/middleware/) |
| `31_cors/` | [CORS (Cross-Origin Resource Sharing)](https://fastapi.tiangolo.com/tutorial/cors/) |
| `32_sql_databases/` | [SQL (Relational) Databases](https://fastapi.tiangolo.com/tutorial/sql-databases/) |
| `33_bigger_applications/` | [Bigger Applications - Multiple Files](https://fastapi.tiangolo.com/tutorial/bigger-applications/) |
| `34_stream_json_lines/` | [Stream JSON Lines](https://fastapi.tiangolo.com/tutorial/stream-json-lines/) |
| `35_server_sent_events/` | [Server-Sent Events (SSE)](https://fastapi.tiangolo.com/tutorial/server-sent-events/) |
| `36_background_tasks/` | [Background Tasks](https://fastapi.tiangolo.com/tutorial/background-tasks/) |
| `37_metadata_and_docs_urls/` | [Metadata and Docs URLs](https://fastapi.tiangolo.com/tutorial/metadata/) |
| `38_static_files/` | [Static Files](https://fastapi.tiangolo.com/tutorial/static-files/) |
| `39_testing/` | [Testing](https://fastapi.tiangolo.com/tutorial/testing/) |
| `40_debugging/` | [Debugging](https://fastapi.tiangolo.com/tutorial/debugging/) |

---

## 02_advanced — Advanced User Guide

公式ドキュメント: https://fastapi.tiangolo.com/advanced/

| フォルダ | 対応ドキュメント |
|---|---|
| `01_stream_data/` | [Stream Data](https://fastapi.tiangolo.com/advanced/stream-data/) |
| `02_path_operation_advanced_configuration/` | [Path Operation Advanced Configuration](https://fastapi.tiangolo.com/advanced/path-operation-advanced-configuration/) |
| `03_additional_status_codes/` | [Additional Status Codes](https://fastapi.tiangolo.com/advanced/additional-status-codes/) |
| `04_return_a_response_directly/` | [Return a Response Directly](https://fastapi.tiangolo.com/advanced/response-directly/) |
| `05_custom_response/` | [Custom Response - HTML, Stream, File, others](https://fastapi.tiangolo.com/advanced/custom-response/) |
| `06_additional_responses_in_openapi/` | [Additional Responses in OpenAPI](https://fastapi.tiangolo.com/advanced/additional-responses/) |
| `07_response_cookies/` | [Response Cookies](https://fastapi.tiangolo.com/advanced/response-cookies/) |
| `08_response_headers/` | [Response Headers](https://fastapi.tiangolo.com/advanced/response-headers/) |
| `09_response_change_status_code/` | [Response - Change Status Code](https://fastapi.tiangolo.com/advanced/response-change-status-code/) |
| `10_advanced_dependencies/` | [Advanced Dependencies](https://fastapi.tiangolo.com/advanced/advanced-dependencies/) |
| `11_advanced_security/01_oauth2_scopes/` | [OAuth2 scopes](https://fastapi.tiangolo.com/advanced/security/oauth2-scopes/) |
| `11_advanced_security/02_http_basic_auth/` | [HTTP Basic Auth](https://fastapi.tiangolo.com/advanced/security/http-basic-auth/) |
| `12_using_the_request_directly/` | [Using the Request Directly](https://fastapi.tiangolo.com/advanced/using-request-directly/) |
| `13_using_dataclasses/` | [Using Dataclasses](https://fastapi.tiangolo.com/advanced/dataclasses/) |
| `14_advanced_middleware/` | [Advanced Middleware](https://fastapi.tiangolo.com/advanced/middleware/) |
| `15_sub_applications_mounts/` | [Sub Applications - Mounts](https://fastapi.tiangolo.com/advanced/sub-applications/) |
| `16_behind_a_proxy/` | [Behind a Proxy](https://fastapi.tiangolo.com/advanced/behind-a-proxy/) |
| `17_templates/` | [Templates](https://fastapi.tiangolo.com/advanced/templates/) |
| `18_websockets/` | [WebSockets](https://fastapi.tiangolo.com/advanced/websockets/) |
| `19_lifespan_events/` | [Lifespan Events](https://fastapi.tiangolo.com/advanced/events/) |
| `20_testing_websockets/` | [Testing WebSockets](https://fastapi.tiangolo.com/advanced/testing-websockets/) |
| `21_testing_events_lifespan/` | [Testing Events: lifespan and startup - shutdown](https://fastapi.tiangolo.com/advanced/testing-events/) |
| `22_testing_dependencies_with_overrides/` | [Testing Dependencies with Overrides](https://fastapi.tiangolo.com/advanced/testing-dependencies/) |
| `23_async_tests/` | [Async Tests](https://fastapi.tiangolo.com/advanced/async-tests/) |
| `24_settings_and_environment_variables/` | [Settings and Environment Variables](https://fastapi.tiangolo.com/advanced/settings/) |
| `25_openapi_callbacks/` | [OpenAPI Callbacks](https://fastapi.tiangolo.com/advanced/openapi-callbacks/) |
| `26_openapi_webhooks/` | [OpenAPI Webhooks](https://fastapi.tiangolo.com/advanced/openapi-webhooks/) |
| `27_including_wsgi/` | [Including WSGI - Flask, Django, others](https://fastapi.tiangolo.com/advanced/wsgi/) |

---

## 03_deployment — Deployment

公式ドキュメント: https://fastapi.tiangolo.com/deployment/

| フォルダ | 対応ドキュメント |
|---|---|
| `01_about_fastapi_versions/` | [About FastAPI versions](https://fastapi.tiangolo.com/deployment/versions/) |
| `02_about_https/` | [About HTTPS](https://fastapi.tiangolo.com/deployment/https/) |
| `03_run_a_server_manually/` | [Run a Server Manually](https://fastapi.tiangolo.com/deployment/manually/) |
| `04_deployment_concepts/` | [Deployments Concepts](https://fastapi.tiangolo.com/deployment/concepts/) |
| `05_server_workers_uvicorn/` | [Server Workers - Uvicorn with Workers](https://fastapi.tiangolo.com/deployment/server-workers/) |
| `06_fastapi_in_containers_docker/` | [FastAPI in Containers - Docker](https://fastapi.tiangolo.com/deployment/docker/) |

---

## 04_how_to — How To - Recipes

公式ドキュメント: https://fastapi.tiangolo.com/how-to/

| フォルダ | 対応ドキュメント |
|---|---|
| `01_graphql/` | [GraphQL](https://fastapi.tiangolo.com/how-to/graphql/) |
| `02_custom_request_and_apiroute_class/` | [Custom Request and APIRoute class](https://fastapi.tiangolo.com/how-to/custom-request-and-route/) |
| `03_conditional_openapi/` | [Conditional OpenAPI](https://fastapi.tiangolo.com/how-to/conditional-openapi/) |
| `04_extending_openapi/` | [Extending OpenAPI](https://fastapi.tiangolo.com/how-to/extending-openapi/) |
| `05_custom_docs_ui_static_assets/` | [Custom Docs UI Static Assets (Self-Hosting)](https://fastapi.tiangolo.com/how-to/custom-docs-ui-assets/) |
| `06_configure_swagger_ui/` | [Configure Swagger UI](https://fastapi.tiangolo.com/how-to/configure-swagger-ui/) |
| `07_testing_a_database/` | [Testing a Database](https://fastapi.tiangolo.com/how-to/testing-database/) |
