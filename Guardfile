guard :rspec, :cmd => 'bundle exec rspec' do
  watch(/^libraries\/(.+)\.rb$/) { 'spec' }
  watch(/^spec\/unit\/(.+)_spec\.rb$/)
  watch('spec/spec_helper.rb')      { 'spec' }
end
