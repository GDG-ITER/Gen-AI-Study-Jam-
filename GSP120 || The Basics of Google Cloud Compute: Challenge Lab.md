# Creating a Virtual Machine || [GSP120]([https://www.cloudskillsboost.google/focuses/3563?parent=catalog](https://www.cloudskillsboost.google/course_templates/754/labs/461563)) ||

## Solution [here](https://youtu.be/FJUsxDrbzLg?si=raKmwvTODJOnyUlF)

### Run the following Commands For Setup

```
export ZONE=""
export INSTANCE_NAME=""
```

### Run the following Commands For TASK 2

```
gcloud compute disks create mydisk --size=200GB \
--zone $ZONE
gcloud compute instances attach-disk $INSTANCE_NAME --disk mydisk --zone $ZONE
```

### Run the following Commands For TASK 3
#### OPEN SSH
```
sudo apt-get update
sudo apt-get install -y nginx
```

### Congratulations 🎉 for Completing the Lab !

#### *Well done!*

#### Don't Forget to Follow the [Instagram](https://www.instagram.com/gdg_iter/) & [YouTube Channel](http://www.youtube.com/@gdgiter)

# [GDG ITER](http://www.youtube.com/@gdgiter)
