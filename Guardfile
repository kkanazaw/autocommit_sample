guard :shell do
  watch /\A**\/*\z/ do |m|
    `git add #{m[0]} && git commit -m 'Automatically commit: #{m[0]}' && git push origin master`
  end
end
