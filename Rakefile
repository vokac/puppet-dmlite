require 'rubygems'
require 'puppetlabs_spec_helper/rake_tasks'

PuppetLint.configuration.fail_on_warnings
PuppetLint.configuration.send('relative')
PuppetLint.configuration.send('disable_80chars')
PuppetLint.configuration.send('disable_class_inherits_from_params_class')
PuppetLint.configuration.send('disable_documentation')
PuppetLint.configuration.send('disable_single_quote_string_with_variables')
PuppetLint.configuration.send('disable_only_variable_string')
PuppetLint.configuration.ignore_paths = ["spec/**/*.pp", "pkg/**/*.pp"]
