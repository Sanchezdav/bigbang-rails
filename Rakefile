# frozen_string_literal: true

require "bundler/gem_tasks"
require "rspec/core/rake_task"
require 'sdoc'
require 'rdoc/task'

RSpec::Core::RakeTask.new(:spec)

RDoc::Task.new do |rdoc|
  rdoc.rdoc_dir = 'doc/rdoc'
  rdoc.options << '--format=sdoc'
  rdoc.template = 'rails'
end

task default: :spec
