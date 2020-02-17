rollout-step-num: 1
replay-start-size: 10000
actor-layer-size: [256, 256]
n-step: 1
dsr-gait-period: 0.6
prioritized-exp-replay: True
critic-l2-reg: 0.0003
loss-entropy-coeff: 0.0
HLC-frequency: 25
total-step-num: 2500000000
task-weight: 0.5
max-test-time: 10
actor-lr: 0.0003
imitation-weight: 0.5
gating-layer-size: [32, 32]
expert-index: None
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
render-eval: False
test-num: 4
epoch-step-num: 5000000
critic-activation-fn: ['relu', 'relu', 'None']
filter-torque: False
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
tau: 0.001
critic-weight-decay: 1e-06
gamma: 0.955
critic-lr: 0.0003
max-path-num: 20
loss-output-diff-coeff: 0
action-bounds: [[-0.39  -2.79   0.66  -0.39  -2.79   0.66  -0.39  -1.884  0.66  -0.39
  -1.884  0.66 ]
 [ 0.39   0.348  2.73   0.39   0.348  2.73   0.39   0.348  2.73   0.39
   0.348  2.73 ]]
max-step-num: 2500000000
record-start-size: 10000.0
loss-output-smooth-coeff: 1.0
state-dim: 25
loss-output-bound-coeff: 0.0
expert-num: 4
interpolation: False
batch-size: 128
actor-activation-fn: ['relu', 'relu', 'None']
bullet-default-PD: False
filter-action: True
LLC-frequency: 500
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
reward-scale: 0.1
max-episode-num: 5000000
actor-l2-reg: 0.0003
train-step-num: 1
env-id: HumanoidBalanceFilter-v0
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
Physics-frequency: 1000
action-dim: 12
squash-action: True
dsr-gait-freq: 1.667
gating-activation-fn: ['relu', 'relu', 'None']
critic-layer-size: [256, 256]
replay-buffer-size: 1000000
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
joint-interpolation: True
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
replay-ratio: 1
actor-weight-decay: 1e-06
max-train-time: 10
epoch-num: 500
gating-index: None
max-path-step: 5000
categorical-distribution: {'n_atoms': 51, 'v_max': 250, 'v_min': -10}
