require 'html-proofer'

task :test do
  sh "bundle exec jekyll build"
  HTMLProofer.check_directory("./_site",{
  		:allow_hash_href=> true,
  		:url_ignore => [/linkedin.com/],
  	}).run
end