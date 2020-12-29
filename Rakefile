task :gen_url do
  puts %Q{buildkite-agent meta-data set --job #{ENV['TRIGGERED_BY_JOB_ID']} "play_url" "https://google.com"}
  `buildkite-agent meta-data set --job #{ENV['TRIGGERED_BY_JOB_ID']} "play_url" "https://google.com"`
end
