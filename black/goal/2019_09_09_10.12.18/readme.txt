state-dim: 25
Physics-frequency: 1000
epoch-step-num: 5000000
loss-output-smooth-coeff: 1.0
gating-activation-fn: ['relu', 'relu', 'None']
epoch-num: 500
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
actor-lr: 0.0003
test-num: 4
gating-index: None
critic-l2-reg: 0.0003
dsr-gait-freq: 1.667
critic-activation-fn: ['relu', 'relu', 'None']
categorical-distribution: {'n_atoms': 51, 'v_max': 250, 'v_min': -10}
squash-action: True
dsr-gait-period: 0.6
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
loss-entropy-coeff: 0.0
replay-start-size: 10000
env-id: HumanoidBalanceFilter-v0
max-test-time: 10
critic-weight-decay: 1e-06
LLC-frequency: 500
batch-size: 128
joint-interpolation: True
loss-output-diff-coeff: 0
action-bounds: [[-0.39  -2.79   0.66  -0.39  -2.79   0.66  -0.39  -1.884  0.66  -0.39
  -1.884  0.66 ]
 [ 0.39   0.348  2.73   0.39   0.348  2.73   0.39   0.348  2.73   0.39
   0.348  2.73 ]]
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
critic-lr: 0.0003
gamma: 0.955
replay-ratio: 1
tau: 0.001
filter-torque: False
train-step-num: 1
expert-num: 4
filter-action: True
prioritized-exp-replay: True
action-dim: 12
critic-layer-size: [256, 256]
imitation-weight: 0.5
actor-activation-fn: ['relu', 'relu', 'None']
actor-weight-decay: 1e-06
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
record-start-size: 10000.0
task-weight: 0.5
reward-scale: 0.1
max-train-time: 10
max-path-num: 20
n-step: 1
loss-output-bound-coeff: 0.0
max-path-step: 5000
gating-layer-size: [32, 32]
total-step-num: 2500000000
rollout-step-num: 1
interpolation: False
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
max-episode-num: 5000000
actor-l2-reg: 0.0003
bullet-default-PD: False
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
max-step-num: 2500000000
expert-index: None
actor-layer-size: [256, 256]
render-eval: False
HLC-frequency: 25
replay-buffer-size: 1000000
