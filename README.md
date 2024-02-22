class VideoEditor:
    def __init__(self, video_file):
        self.video_file = video_file

    def replace_video(self, new_video_file):
        print(f"Replaced video with: {new_video_file}")
        self.video_file = new_video_file

# Example usage
editor = VideoEditor("old_video.mp4")
editor.replace_video("new_video.mp4")
