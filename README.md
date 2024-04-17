## Multimodal models as zero-shot rewards

running dqn on base modified cartpole environment (no termination) with wandb + video logging
`python dqn_gym.py --track --capture-video --env-id="CLIPRewardedCartPoleEnv" --save-model --model-id=""`

running dqn on base modified cartpole environment (no termination) with clip vit backbone, wandb + video logging
`python dqn_gym.py --track --capture-video --env-id="CLIPRewardedCartPoleEnv" --save-model --model-id="clip_vit"`

