require "html/proofer"

task :default => [:test]

task :test do
	HTML::Proofer.new("./_site", {
		:href_ignore => [
			"#"
		],
	}).run
end