# analysis_options.yaml
Flutter / Dart analysis_options.yaml for perfectionists.

```
# This file configures the analyzer, which statically analyzes Dart code to
# check for errors, warnings, and lints.
#
# The issues identified by the analyzer are surfaced in the UI of Dart-enabled
# IDEs (https://dart.dev/tools#ides-and-editors). The analyzer can also be
# invoked from the command line by running `flutter analyze`.

# The following line activates a set of recommended lints for Flutter apps,
# packages, and plugins designed to encourage good coding practices.
include: package:flutter_lints/flutter.yaml

linter:
  # The lint rules applied to this project can be customized in the
  # section below to disable rules from the `package:flutter_lints/flutter.yaml`
  # included above or to enable additional rules. A list of all available lints
  # and their documentation is published at
  # https://dart-lang.github.io/linter/lints/index.html.
  #
  # Instead of disabling a lint rule for the entire project in the
  # section below, it can also be suppressed for a single line of code
  # or a specific dart file by using the `// ignore: name_of_lint` and
  # `// ignore_for_file: name_of_lint` syntax on the line or in the file
  # producing the lint.
  rules:
    avoid_print: true
    prefer_single_quotes: true
    void_checks: true
    always_declare_return_types: true
    unnecessary_this: true
    always_specify_types: false
    use_named_constants: true
    always_put_required_named_parameters_first: true
    always_put_control_body_on_new_line: true
    curly_braces_in_flow_control_structures: true
    prefer_final_locals: true
    unawaited_futures: true
    prefer_contains: true
    avoid_empty_else: true
    always_require_non_null_named_parameters: true
    always_use_package_imports: false
    avoid_relative_lib_imports: true
    valid_regexps: true
    prefer_relative_imports: true
    use_build_context_synchronously: true
    use_test_throws_matchers: true
    use_super_parameters: true
    use_string_in_part_of_directives: true
    use_setters_to_change_properties: true
    use_rethrow_when_possible: true
    use_raw_strings: true
    use_if_null_to_convert_nulls_to_bools: true
    use_function_type_syntax_for_parameters: true
    use_key_in_widget_constructors: true
    use_is_even_rather_than_modulo: true
    use_enums: true
    annotate_overrides: true
    avoid_bool_literals_in_conditional_expressions: true
    avoid_double_and_int_checks: true
    avoid_dynamic_calls: true
    avoid_function_literals_in_foreach_calls: true
    avoid_init_to_null: true
    avoid_null_checks_in_equality_operators: true
    avoid_shadowing_type_parameters: true
    avoid_single_cascade_in_expression_statements: true
    avoid_slow_async_io: true
    avoid_type_to_string: true
    avoid_types_as_parameter_names: true
    avoid_unnecessary_containers: true
    avoid_unused_constructor_parameters: true
    avoid_void_async: true
    camel_case_extensions: true
    camel_case_types: true
    cancel_subscriptions: true
    await_only_futures: true
    control_flow_in_finally: true
    dangling_library_doc_comments: true
    depend_on_referenced_packages: true
    directives_ordering: true
    file_names: true
    package_names: true
    flutter_style_todos: true
    type_annotate_public_apis: true
    omit_local_variable_types: true
    avoid_types_on_closure_parameters: true
    library_prefixes: true
    non_constant_identifier_names: true
    lines_longer_than_80_chars: true
    slash_for_doc_comments: true
    implementation_imports: true
    prefer_adjacent_string_concatenation: true
    unnecessary_brace_in_string_interps: true
    prefer_collection_literals: true
    prefer_is_not_empty: true
    prefer_is_empty: true
    prefer_iterable_whereType: true
    prefer_function_declarations_over_variables: true
    unnecessary_lambdas: true
    prefer_equal_for_default_values: true
    unnecessary_getters_setters: true
    prefer_initializing_formals: true
    empty_constructor_bodies: true
    unnecessary_new: true
    unnecessary_const: true
    use_to_and_as_if_applicable: true
    one_member_abstracts: true
    avoid_classes_with_only_static_members: true
    prefer_mixin: true
    prefer_final_fields: true
    avoid_returning_this: true
    prefer_typing_uninitialized_variables: true
    type_init_formals: true

# Additional information about this file can be found at
# https://dart.dev/guides/language/analysis-options
analyzer:
  exclude:
    - 'lib/**/*.freezed.dart'
    - 'lib/**/*.g.dart'
  plugins:
    - custom_lint
  errors:
    invalid_annotation_target: ignore
```
