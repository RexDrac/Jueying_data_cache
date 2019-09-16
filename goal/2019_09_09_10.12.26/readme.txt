state-dim: 25
gating-layer-size: [32, 32]
total-step-num: 2500000000
tau: 0.001
imitation-weight: 0.5
squash-action: True
Physics-frequency: 1000
dsr-gait-period: 0.6
replay-ratio: 1
max-test-time: 10
train-step-num: 1
actor-l2-reg: 0.0003
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
actor-layer-size: [256, 256]
epoch-num: 500
replay-buffer-size: 1000000
action-dim: 12
critic-activation-fn: ['relu', 'relu', 'None']
reward-scale: 0.1
actor-activation-fn: ['relu', 'relu', 'None']
critic-weight-decay: 1e-06
replay-start-size: 10000
gating-activation-fn: ['relu', 'relu', 'None']
interpolation: False
loss-output-diff-coeff: 0
loss-output-smooth-coeff: 1.0
max-path-num: 20
batch-size: 128
rollout-step-num: 1
epoch-step-num: 5000000
max-episode-num: 5000000
loss-output-bound-coeff: 0.0
actor-weight-decay: 1e-06
dsr-gait-freq: 1.667
categorical-distribution: {'v_max': 250, 'v_min': -10, 'n_atoms': 51}
max-path-step: 5000
test-num: 4
record-start-size: 10000.0
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
expert-num: 4
actor-lr: 0.0003
action-bounds: [[-0.39  -2.79   0.66  -0.39  -2.79   0.66  -0.39  -1.884  0.66  -0.39
  -1.884  0.66 ]
 [ 0.39   0.348  2.73   0.39   0.348  2.73   0.39   0.348  2.73   0.39
   0.348  2.73 ]]
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
max-train-time: 10
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
critic-l2-reg: 0.0003
critic-layer-size: [256, 256]
render-eval: False
LLC-frequency: 500
env-id: HumanoidBalanceFilter-v0
filter-torque: False
max-step-num: 2500000000
prioritized-exp-replay: True
bullet-default-PD: False
loss-entropy-coeff: 0.0
filter-action: True
gating-index: None
task-weight: 0.5
n-step: 1
joint-interpolation: True
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
expert-index: None
critic-lr: 0.0003
HLC-frequency: 25
gamma: 0.955
