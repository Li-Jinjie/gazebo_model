# gazebo_model

An attempt to store large environmental meshes in git submodules.

Note: this repo should be put under aerial_robot_simulation/gazebo_model, may nameed as model/.

So the repo structure is like this:

```
aerial_robot_simulation/
└── gazebo_model/
    └── world/
    └── model/  # this repo, renamed from gazebo_model to model
```

This file structure has been added as git submodule using the following command:

```
git submodule add <this_repo_url> aerial_robot_simulation/gazebo_model/model
```

If you want to make the whole gazebo_model a repo, you have to extract all files out of the git history.
