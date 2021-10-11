from pytube import Youtube
link = input("Enter URL")
video = Youtube(link)
stream = video.streams.get_highest_resolution()
stream.download()
