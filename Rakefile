require 'html-proofer'

task :test do
  sh "bundle exec jekyll build"
  HTMLProofer.check_directory("./_site",{
  		:allow_hash_href=> true,
  		:typhoeus => {
    		:headers => { "User-Agent" => "Mozilla/5.0 (Windows NT 6.1; WOW64; rv:40.0) Gecko/20100101 Firefox/40.1" }
    	}
  	}).run
end