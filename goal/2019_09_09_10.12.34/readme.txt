gating-index: None
batch-size: 128
gamma: 0.955
filter-torque: False
actor-weight-decay: 1e-06
train-step-num: 1
dsr-gait-period: 0.6
categorical-distribution: {'n_atoms': 51, 'v_min': -10, 'v_max': 250}
max-test-time: 10
critic-l2-reg: 0.0003
epoch-step-num: 5000000
gating-layer-size: [32, 32]
replay-start-size: 10000
max-path-num: 20
critic-weight-decay: 1e-06
rollout-step-num: 1
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
Physics-frequency: 1000
loss-output-bound-coeff: 0.0
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
bullet-default-PD: False
reward-scale: 0.1
actor-lr: 0.0003
actor-activation-fn: ['relu', 'relu', 'None']
critic-activation-fn: ['relu', 'relu', 'None']
task-weight: 0.5
squash-action: True
record-start-size: 10000.0
dsr-gait-freq: 1.667
loss-output-diff-coeff: 0
LLC-frequency: 500
prioritized-exp-replay: True
max-train-time: 10
action-bounds: [[-0.39  -2.79   0.66  -0.39  -2.79   0.66  -0.39  -1.884  0.66  -0.39
  -1.884  0.66 ]
 [ 0.39   0.348  2.73   0.39   0.348  2.73   0.39   0.348  2.73   0.39
   0.348  2.73 ]]
replay-buffer-size: 1000000
max-path-step: 5000
joint-interpolation: True
interpolation: False
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
render-eval: False
expert-index: None
max-episode-num: 5000000
gating-activation-fn: ['relu', 'relu', 'None']
actor-layer-size: [256, 256]
env-id: HumanoidBalanceFilter-v0
filter-action: True
action-dim: 12
tau: 0.001
actor-l2-reg: 0.0003
test-num: 4
epoch-num: 500
critic-layer-size: [256, 256]
expert-num: 4
critic-lr: 0.0003
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
total-step-num: 2500000000
loss-output-smooth-coeff: 1.0
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
state-dim: 25
replay-ratio: 1
max-step-num: 2500000000
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
loss-entropy-coeff: 0.0
n-step: 1
imitation-weight: 0.5
HLC-frequency: 25
