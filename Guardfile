# A sample Guardfile
# More info at https://github.com/guard/guard#readme
guard :shell do
   watch (%r{(ex|exs)$}) do |m|
	puts m
	`mix test`
   end
end
