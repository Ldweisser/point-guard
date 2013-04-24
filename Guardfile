# Guardfile
# More info at https://github.com/guard/guard#readme

# guard-concat
guard :concat, type: "js", 
  files: %w(
    libs/jquery-1.9.1.min
    plugins/jquery-plugin-1 
    plugins/jquery-plugin-2 
    plugins/jquery-plugin-3 
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