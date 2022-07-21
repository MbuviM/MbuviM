### Hi there 👋
I'm Yvonne Mwende Mbuvi.

A data scientist who is also interested in Machine Learning, Artificial Intelligence and Robotics.

Hope you'll enjoy all the projects created in the repositories.

🔭 I’m currently working on data science projects

🌱 I’m currently learning data science
### Now Playing — Spotify 🎧
<p>
<a href=”https://spotify-github-profile.vercel.app/api/view.svg?uid=0dyt0z4xdnug7teutmvub5la8&redirect=true">
<img src= "https://spotify-github-profile.vercel.app/api/view?uid=0dyt0z4xdnug7teutmvub5la8&cover_image=true&theme=default"/>
</a>
</p>
                                                                                                                           
import sys
import time
def progressBar(count, total, suffix=''):
    barLength = 60
    filledLength = int(round(barLength * count / float(total)))

    percent = round(100.0 * count / float(total))
    bar = '=' * filledLength + '-' * (barLength - filledLength)

    sys.stdout.write('[%s] %s%s.....%s\r' % (bar, percent, '%', suffix))
    sys.stdout.flush()

for i in range(10):
    time.sleep(1)
    progressBar(i, 10)

