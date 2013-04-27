# Guardfile
# More info at https://github.com/guard/guard#readme

# guard-concat
# Add bower components here. Do not add .js at the end of the file.
guard :concat, type: "js", 
  files: %w(
    libs/jquery-1.9.1.min
    app
  ), 
  input_dir: "js", 
  output: "js/app.min"

# guard-sass
guard 'sass', 
	:input => 'scss', 
	:output => 'css', 
	:style => :compressed

# guard-livereload
guard 'livereload' do
  watch(%r{.+\.(css|html|js)$})
end